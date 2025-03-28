# ft_transcendence

로컬 환경에서 실행하기 위해 `.env` 파일을 설정해야 합니다.

frontend, backend를 받아 아래와 같은 구조로 두고 도커를 실행한 상태에서 ./docker에서 make 명령어를 입력합니다.

### 프로젝트 구조
```
.
└── docker
    ├── Makefile
    ├── README.md
    └── srcs
        ├── .env
        ├── docker-compose.yml
        ├── nest
        │   ├── backend/
        │   │   └── .env
        │   └── Dockerfile
        ├── next
        │   ├── frontend/
        │   │   └── .env
        │   └── Dockerfile
        └── postgresql
            ├── Dockerfile
            ├── config
            │   ├── pg_hba.conf
            │   └── postgresql.conf
            └── tools
                └── database.sh
```

### Versions
```
  "dependencies": {
    "@nestjs/common": "^10.0.3",
    "@nestjs/config": "^3.0.0",
    "@nestjs/core": "^10.0.3",
    "@nestjs/jwt": "^10.1.0",
    "@nestjs/mapped-types": "^2.0.2",
    "@nestjs/passport": "^10.0.0",
    "@nestjs/platform-express": "^10.0.3",
    "@nestjs/platform-socket.io": "^10.0.3",
    "@nestjs/typeorm": "^10.0.0",
    "@nestjs/websockets": "^10.0.3",
    "bcryptjs": "^2.4.3",
    "class-transformer": "^0.5.1",
    "class-validator": "^0.14.0",
    "config": "^3.3.9",
    "passport": "^0.6.0",
    "passport-jwt": "^4.0.1",
    "pg": "^8.11.1",
    "typeorm": "^0.3.17"
  },
  "devDependencies": {
    "@nestjs/cli": "^10.0.5",
    "@nestjs/schematics": "^10.0.1",
    "@nestjs/testing": "^10.0.3",
    "@types/express": "^4.17.17",
    "@types/jest": "29.5.2",
    "@types/node": "20.3.2",
    "@types/passport-jwt": "^3.0.8",
    "@types/supertest": "^2.0.12",
    "@typescript-eslint/eslint-plugin": "^5.60.1",
    "@typescript-eslint/parser": "^5.60.1",
    "eslint": "^8.43.0",
    "eslint-config-prettier": "^8.8.0",
    "eslint-plugin-prettier": "^4.2.1",
    "jest": "29.5.0",
    "prettier": "^2.8.8",
    "source-map-support": "^0.5.21",
    "supertest": "^6.3.3",
    "ts-jest": "29.1.0",
    "ts-loader": "^9.4.3",
    "ts-node": "^10.9.1",
    "tsconfig-paths": "4.2.0",
    "typescript": "^5.1.3"
```
