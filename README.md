# ft_transcendence

### package.json
```
{
  "name": "ft-ts-backend",
  "version": "0.0.1",
  "description": "",
  "author": "",
  "private": true,
  "license": "UNLICENSED",
  "scripts": {
    "build": "nest build",
    "format": "prettier --write \"src/**/*.ts\" \"test/**/*.ts\"",
    "start": "nest start",
    "start:dev": "nest start --watch",
    "start:debug": "nest start --debug --watch",
    "start:prod": "node dist/main",
    "lint": "eslint \"{src,apps,libs,test}/**/*.ts\" --fix",
    "test": "jest",
    "test:watch": "jest --watch",
    "test:cov": "jest --coverage",
    "test:debug": "node --inspect-brk -r tsconfig-paths/register -r ts-node/register node_modules/.bin/jest --runInBand",
    "test:e2e": "jest --config ./test/jest-e2e.json"
  },
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
  },
  "jest": {
    "moduleFileExtensions": [
      "js",
      "json",
      "ts"
    ],
    "rootDir": "src",
    "testRegex": ".*\\.spec\\.ts$",
    "transform": {
      "^.+\\.(t|j)s$": "ts-jest"
    },
    "collectCoverageFrom": [
      "**/*.(t|j)s"
    ],
    "coverageDirectory": "../coverage",
    "testEnvironment": "node"
  }
}

```