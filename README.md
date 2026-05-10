# Let-s_Go_DreamTeam

## 📣 Convention
### Code Style
[Swift Style Guide](https://github.com/StyleShare/swift-style-guide)를 따릅니다.

### Commit
**- Tag**
<table>
  <thead>
    <tr>
      <th align="center">태그</th>
      <th align="center">사용하는 부분</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><b>[Feat]</b></td>
      <td align="left">새로운 기능 구현</td>
    </tr>
    <tr>
      <td align="center"><b>[Fix]</b></td>
      <td align="left">버그, 오류 해결</td>
    </tr>
    <tr>
      <td align="center"><b>[Chore]</b></td>
      <td align="left">코드 수정, 내부 파일 수정 등 중요도가 낮은 기타 작업</td>
    </tr>
    <tr>
      <td align="center"><b>[Add]</b></td>
      <td align="left">라이브러리 또는 에셋 추가</td>
    </tr>
    <tr>
      <td align="center"><b>[Delete]</b></td>
      <td align="left">쓸모없는 코드 삭제</td>
    </tr>
    <tr>
      <td align="center"><b>[Docs]</b></td>
      <td align="left">README나 WIKI 등의 문서 개정</td>
    </tr>
    <tr>
      <td align="center"><b>[Refactor]</b></td>
      <td align="left">기존 코드 리팩토링 또는 구조 개선</td>
    </tr>
    <tr>
      <td align="center"><b>[Setting]</b></td>
      <td align="left">프로젝트 관련 설정 변경</td>
    </tr>
    <tr>
      <td align="center"><b>[Merge]</b></td>
      <td align="left">Pull Develop</td>
    </tr>
  </tbody>
</table>

**- Message**
```
(커밋 메세지 형식)
[종류] #이슈번호 - 작업 내용

(기본 커밋 메시지 예시)
[Feat]: #1 - 메인 UI 구현

(Conflict 해결 시)
[Merge]: #이슈번호 - Conflict 해결 

(PR을 develop에 merge 시)
[Merge]: #이슈번호 - 작업 내용 간략히
```

## 🐾 Git Flow
<img src="https://github.com/user-attachments/assets/f551fbc8-a8c0-4c11-8749-8ba8dd3bfa92" width="600" alt="">

**Default Branch & PR Target : `develop`**

모든 개발은 `develop` 브랜치를 중심으로 진행됩니다.

```
1. 작업할 내용에 대해 이슈를 판다. (이슈 제목: [태그] 작업 내용)

2. develop 브랜치로부터 새 브랜치를 만든다. (브랜치 명: 타입/#이슈번호)
  - 브랜치 파기 전 최신화 된 develop 브랜치 pull 받기

3. 만든 브랜치에서 작업한다.

4. 커밋은 쪼개서 작성하며 컨벤션을 따라 메시지를 작성한다.

5. 작업할 내용을 다 끝내면 에러 없이 잘 실행되는지 확인 한 후 push 한다.
  - PR 올리기 전 작업 브랜치에 develop 브랜치 pull 받은 뒤 충돌을 해결한 후 push 하는 것을 권장

6. PR을 작성한 후, 팀원들의 코드리뷰를 반영한 뒤 develop 브랜치에 merge 한다.
  - 깃허브 내에서 merge 할 때 메시지 변경하기 ([Merge]: #이슈번호 - 작업 내용)
```
