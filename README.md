# movie-lab

실습하면서 겪은 오류

<img width="925" height="976" alt="image" src="https://github.com/user-attachments/assets/a39d9fb9-9647-42ed-af85-1dc71f5b9d97" />

노트북에서 실습할 때 발생한 오류이다.

파일의 접근권한과 관련된 오류로 현재 노트북의 상태가 파일 옮기기, 새 폴더 생성 등의 간단한 작업 조차도 관리자 권한을 요구하는 상태라서 발생할 가능성이 있다.

집의 데스크탑 기기로 다시 실습을 진행할 시 문제 없이 npm ci가 실행된다

<img width="577" height="363" alt="image" src="https://github.com/user-attachments/assets/bf515822-d97f-439c-8619-04fec30beb05" />

<img width="588" height="363" alt="스크린샷 2026-10-08 211304" src="https://github.com/user-attachments/assets/58052caf-5d25-499d-8dd3-54e71803a109" />

<img width="520" height="219" alt="스크린샷 2026-10-08 212037" src="https://github.com/user-attachments/assets/09747d2e-8c0c-4f86-a4f8-c57f206e0fba" />

Window 보안 상의 이유로 파일의 일부분이 차단됨

해결법 : 원본 파일(압축을 풀기전)의 속성에 들어가 보안 차단 해제를 체크한 후 다시 압축풀기

<br>
<br>
<br>
<br>
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/c23b167c-4d28-4aba-b258-a713fc25c6f2" />

npm run build를 통해 생성된 dist 안의 파일들을 github에 업로드 한 후 pages에 정적 배포한 주소와 곧 바로 실행되는 actions의 자동화 배포의 주소가 같다
