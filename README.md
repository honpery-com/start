# wiki

## 端口占用

- [x] `9000`: go-api
- [x] `9100`: graphql-api
- [x] `9200`: web
- [x] `9300`: admin
- [ ] `9400`
- [ ] `9500`

## go-api
> 后端服务，隐藏在内网，无状态。

#### 技术选型
- [go](http://golang.com/)
- [gin](https://gin-gonic.github.io/gin/)
- [mgo](http://labix.org/mgo)
- [mongo](https://www.mongodb.com/)

#### 模块
- [ ] users
- [ ] articles
- [ ] categories
- [ ] tags

## graphql-api
> 后端接口封装graphql风格，对外开放，有状态。

#### 技术选型
- [TypeScript](https://www.typescriptlang.org/)
- [koa](https://github.com/koajs/koa)
- [graphql](http://graphql.org/)
- [happy-graphql](https://github.com/honpery/happy-graphql)

#### 模块
- query
    - [ ] tags / tag
    - [ ] articles / article
    - [ ] categories / category
    - viewer
- mutation
    - [ ] login / register
    - [ ] article(create, update, delete)
    - [ ] tag(create, udpate, delete)
    - [ ] category(create, update, delete)

## web
> web端，主要包括home和blog。

#### 技术选型
- [TypeScript](https://www.typescriptlang.org/)
- [React](https://facebook.github.io/react/)
- [koa](https://github.com/koajs/koa)

#### 模块
- home
    - [ ] index
    - [ ] about
- blog
    - [ ] article
    - [ ] archive

## admin
> 后台管理系统。

#### 技术选型
- [TypeScript](https://www.typescriptlang.org/)
- [Angular](https://angular.io/)

#### 模块
- home
- article
- basic
    - category
    - tag
- user