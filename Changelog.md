## Unreleased
- Loosened dependency version requirements for `base64`, `url`, and `serde_urlencoded`
- Update depenendcy major versions across the board
- Remove `async-trait` in favor of native async traits
- Use async filesystem I/O in async functions
- Simplify file I/O for media uploads
- Cleanup assorted Clippy lints

## 0.7.0 (2021/03/26)
- updated twapi-reqwest 0.0
- updated tokio 1.0

## 0.6.0 (2020/02/01)
- add reqwest async/await
- separate reqwest to twapi-reqwest

## 0.5.2 (2019/10/10)
- modify url encode modify * and ~ for statuses update

## 0.5.1 (2019/10/10)
- modify space url encode from + to %20 for statuses upadate including space
- related crate version up

## 0.5.0 (2019/06/28)
- separate oauth to twapi-oauth
- apply edition 2018

## 0.4.3 (2019/04/25)
- modify sample in Readme.md

## 0.4.2 (2019/04/20)
- related crate version up

## 0.4.1 (2018/05/14)
- add check waitnig processing_info at post_media_upload_chunk
- related crate version up

## 0.4.0 (2018/03/23)
- add account activity api
- add account activity web applicaiton example

## 0.3.1 (2018/03/19)
- add oauth web applicaiton example

## 0.3.0 (2018/03/17)
- add request_token
- add access_token

## 0.2.0 (2018/03/09)
- add media apis
- add TwapiResponse

## 0.1.0 (2018/03/06)
- first release!
