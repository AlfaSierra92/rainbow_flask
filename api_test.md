A few lines to test restful apis.
```bash
curl -v http://127.0.0.1:5000/api/v1/colors/red
curl -v http://127.0.0.1:5000/api/v1/colors/
curl -d '{"name": "red","red": 255,"green": 0,"blue": 0}' -H "Content-Type: application/json" -v -X POST http://127.0.0.1:5000/api/v1/colors/red
curl -X DELETE -v http://127.0.0.1:5000/api/v1/colors/yellow
curl -X GET -v http://127.0.0.1:5000/api/v1/colors/
curl -X DELETE -v http://127.0.0.1:5000/api/v1/colors/
curl -X DELETE -v http://127.0.0.1:5000/api/v1/colors/blue
curl -X DELETE -v http://127.0.0.1:5000/api/v1/colors/gb
curl -X DELETE -v http://127.0.0.1:5000/api/v1/colors/green
curl -X DELETE -v http://127.0.0.1:5000/api/v1/colors/red
curl -d '{"name": "red","red": 255,"green": 0,"blue": 0}' -H "Content-Type: application/json" -v -X PUT http://127.0.0.1:5000/api/v1/colors/red
curl -v http://127.0.0.1:5000/api/v1/colors/viva
curl -d '{"name": "viva","red": 245,"green": 2,"blue": 255}' -H "Content-Type: application/json" -v -X PUT http://127.0.0.1:5000/api/v1/colors/viva
curl -d '{"name": "viva","red": 245,"green": 2,"blue": 255}' -H "Content-Type: application/json" -v -X POST http://127.0.0.1:5000/api/v1/colors/viva
curl -d '{"name": "viva","red": 245,"green": 2,"blue": 25}' -H "Content-Type: application/json" -v -X POST http://127.0.0.1:5000/api/v1/colors/viva
curl -d '{"name": "viva","red": 245,"green": 2,"blue": 25}' -H "Content-Type: application/json" -v -X POST http://127.0.0.1:5000/api/v1/colors/red
curl -v http://127.0.0.1:5000/api/v1/colors/black
curl -v http://127.0.0.1:5000/api/v1/colors/yellow
curl -v http://127.0.0.1:5000/api/v1/colors/white
curl -v http://127.0.0.1:5000/api/v1/color/
curl http://127.0.0.1:5000/api/v1/colors/
```