# cloudmorph-demo-guestbook

CloudMorph CD 데모용 방명록 앱. 이 저장소에 push 하면 CloudMorph 가 GitHub webhook 으로 받아
분석 → 배포(로컬 Docker + Google Cloud Run) → 실패 시 자가치유 → 공개 URL 발급을 자동으로 수행한다.
`DATABASE_URL` 이 있으면 PostgreSQL, 없으면 SQLite.
