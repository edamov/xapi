# Documentation

http://www.mikestowe.com/2014/12/api-spec-comparison-tool.php

Сравнение спецификаций и тулзовин для документирования:

- что сравнивать:
 * Open API (Swagger 2.0)
 * RAML
 * API Blueprint
 * Postman
 * APIDoc

| Criteria / Spec | RAML | Open API | API Blueprint |
| --- | --- | --- | --- |
| Github stars |  2 221 | 3 534 | 4 092 |
| Community activity |   |  |  |
| Spec format | yaml | yaml/json | MSON (Markdown) |
| Spec Documentation | Good | 2:2 | 3:2 |
| Documentation first | Yes | Yes | Yes |
| Auth support | OAuth1, OAuth2, Basic, Digest, custom | 2:3 | 3:3 |
| Status Codes support | Yes | Yes | 3:4 |
| Templates support (traits, schemas for re-using) | Yes | Yes | 3:5 |
| File uploads support | Yes | Yes | 3:6 |
| Versioning support | Yes | 2:7 | 3:7 |
| Mock server generator | https://github.com/jasir/php-raml-server | 2:8 | 3:8 |
| Test tools (schema validation) | Yes | Yes | 3:9 |
| PHP code generator | No | Yes | 3:10 |
| PHP spec parser | Yes | Yes | 3:11 |
| PHP SDK generator | No | Yes | 3:12 |
| PHP Frameworks support | poor Symfony2 bundle | Laravel, Yii, Symfony, Cake | 3:12 |
| Ease getting started | Easy | Easy | 3:13 |
| Static docs generator | Yes | No | 3:14 |
| Playground generator | Yes | Yes | 3:15 |
| IDE support | Yes (Atom) | Yes (PHPStorm, Atom) | No |


- Events (crud, apply|deny|maybe, search), Users (crud, forgot password, change password, follow), Categories(or tags) Auth (OAuth2, JWT)