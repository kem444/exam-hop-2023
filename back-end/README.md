# Todo list backend service

![todo-front](./todo-front.png)

Дараах зааврын дагуу todo list service бичих ба хийж дуусад урьдчилан бэлдсэн [Front-end](../front-end/) кодтой холбох юм.

## A variant

- `GET http://localhost:5000` руу хандахад ‘Todo list backend’ гэж буцаах.  / 1 оноо /
- `GET http://localhost:5000/test` руу хандахад ‘This is test endpoint’ гэж буцаах. / 1 оноо /
- Mongodb-тэй холбох  terminal дээр `Successfully connected mongodb` гэж харуулах  / 5 оноо /
- Task schema uusgeh 
  - text : string / 1 оноо /
  - isDone : boolean, default: false / 1 оноо /
  - createdDate: date  / 1 оноо /
- `GET http://localhost:5000/list` руу хандахад listee array aar ugdug baina. / 1 оноо /
  - ene endpoint ymar neg ym butsaadag bol  / 1 оноо /
  - Mongoose query bichsen bol hagas onoo  / 1 оноо /
  - Query-ээс awsan utgaa butsaadag bol  / 1 оноо /
- `GET http://localhost:5000/count` руу хандахад huselt yvuulaad. isDone taskuudiin toog awna. / 1 оноо /
  - ene endpoint ymar neg ym butsaadag bol 1 / 1 оноо /
  - Mongoose query bichsen bol hagas onoo 2 / 1 оноо /
  - Query-ээс awsan utgaa butsaadag bol 2 / 1 оноо /
- `POST http://localhost:5000/add` руу хандахад huselteer task nemeh POST / 1 оноо /
  - ene endpoint ymar neg ym butsaadag bol 1 / 1 оноо /
  - Mongoose query bichsen bol hagas onoo 2 / 1 оноо /
  - Query-ээс awsan utgaa butsaadag bol 2 / 1 оноо /
- `DELETE http://localhost:5000/delete` руу хандахад huselteer task ustgah. Header deer id damjuulna. DELETE / 1 оноо /
  - ene endpoint ymar neg ym butsaadag bol 1 / 1 оноо /
  - Mongoose query bichsen bol hagas onoo 2 / 1 оноо /
  - Query-ээс awsan utgaa butsaadag bol 2 / 1 оноо /
- `PATCH http://localhost:5000/update` руу хандахад huselt yvuulaad. headereer id damjuulad textee zasah PATCH / 1 оноо /
  - ene endpoint ymar neg ym butsaadag bol 1 / 1 оноо /
  - Mongoose query bichsen bol hagas onoo 2 / 1 оноо /
  - Query-ээс awsan utgaa butsaadag bol 2 / 1 оноо /
- `PATCH http://localhost:5000/checked` руу хандахад huselt yvuulaad. isDone uurchluh. PATCH / 1 оноо /
  - ene endpoint ymar neg ym butsaadag bol 1 / 1 оноо /
  - Mongoose query bichsen bol hagas onoo 2 / 1 оноо /
  - Query-ээс awsan utgaa butsaadag bol 2 / 1 оноо /
- Router ashiglasan eseh 3 / 1 оноо /
  fronttoi holboh - 7 / 1 оноо /
