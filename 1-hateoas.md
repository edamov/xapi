# HATEOAS

http://sookocheff.com/post/api/on-choosing-a-hypermedia-format/

https://habrahabr.ru/post/144259/

http://phalt.co/what-is-hateoas/

https://jeffknupp.com/blog/2014/06/03/why-i-hate-hateoas/

http://blogs.mulesoft.com/dev/api-dev/api-best-practices-hypermedia-part-1/
http://blogs.mulesoft.com/dev/api-dev/api-best-practices-hypermedia-part-3/
http://www.slideshare.net/mikestowe/hypermedia-the-good-the-bad-and-the-ugly

http://apievangelist.com/2014/08/05/the-hypermedia-api-debate-sorry-reasonable-just-does-not-sell/

http://timelessrepo.com/haters-gonna-hateoas

https://github.com/json-api/json-api/issues/98



### Glossary

* HATEOAS
* HYPERMEDIA
* JSON-LD
* Hydra
* JSON API
* HAL

Make the API browsing easier.
Allow to see the relations between locations and photos.
Bring a potential flexibility as you can modify the provided links without impacting the consumers hoping those consumers use the provided links…

### За:

* RESTful
* Урлы не хардкодятся на стороне клиента, дает гибкость в плане последующих изменений ссылок на ресурсы
* Облегчает "просмотр" АПИ (как человеком так и машиной)

### Против:

* Больше времени на разработку
* Избыточность
* Клиенту сложнее разбирать ответы от АПИ, если отсутствуют библиотеки для этого
* Клиенту в большинстве случаев приходится дожидаться ответа для отправки следующего запроса

В реальности, чтобы оценить все достоинства и недостатки лучше попробовать на личном опыте.