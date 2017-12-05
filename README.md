# 보안 설정
http://uxicode.tistory.com/entry/Nodejs%EB%A1%9C-%EA%B0%84%EB%8B%A8%ED%95%98%EA%B2%8C-%EB%A9%94%EC%9D%BC%EB%B3%B4%EB%82%B4%EA%B8%B0-nodemailer
여기를 보시고 gmail 사용시 몇 가지 보안 설정을 해야 합니다.
현재 gsuite 을 사용하기에 도메인 owner만 바꿀 수 있는 설정도 있기 때문에 테스트는 개인 메일 혹은 gmail이 아닌 다른 메일로 해 보셔야할것 같습니다. 

# Jober team
./creds.js 에서 개인 이메일 정보 입력 후 테스트 해 주세요 (주의!! git commit 해서 올리지 말아주세요!)
./index.js 에서 Jack, Joe 들의 이메일을 받아서 테스트 할 수 있는 메일로 바꿔주세요

# html template used
이 예제에서는 handlebar 라는 템플릿 뷰 엔진이 사용되었습니다.

# Node.JS Email Templates

Sending templated emails with Node.JS.

**NOTE**: `email-templates` version 3 contains breaking changes that are incompatible with this exact code. I'll add a branch to this repo that contains working code for `email-templates` version 3, otherwise you can install `email-templates@2` or clone this repo and install the packages from `package.json` and it should work fine.

## Setup from scratch

    $ mkdir nodejs-template-emails
    $ cd nodejs-template-emails
    $ npm init
    $ npm install --save nodemailer email-templates handlebars bluebird

## Setup from repo

    $ git clone https://github.com/GeekLaunch/nodejs-template-emails.git
    $ cd nodejs-template-emails
    $ npm install

[Video Tutorial](https://youtu.be/9zPZ9yJML6E)
