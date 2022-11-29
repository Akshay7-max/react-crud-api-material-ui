JSON server -:
for making fake api & jismay humara data raheygaa.
https://www.npmjs.com/package/json-server 

Run multiple commands concurrently. 
https://www.npmjs.com/package/concurrently

follow above line & perform some installiation
json-server --watch db.json  --port 3333

React Router DOM 
for routing purpose.
https://www.npmjs.com/package/react-router-dom

Material ui & icon
https://v4.mui.com/getting-started/installation/
 
Axios 
api may kaise request send karya ge & post data kaise send kary ge by 
using axios
https://www.npmjs.com/package/axios

db.json  -:
{
  "students": [
    {
      "id": 1,
      "stuname": "Pappu Splander",
      "email": "pappu.splender@123gmail.com"
    },
    {
      "id": 2,
      "stuname": "Ismile Bhai",
      "email": "ismile.bhai@786rediffmail.com"
    },
    {
      "stuname": "Akshay Valimikrao Kumbhare",
      "email": "akshay.kumbhare124@gmail.com",
      "id": 3
    },
    {
      "stuname": "Sunju Singhayaniyaa",
      "email": "sunju.singhayaniyaa@femail.com",
      "id": 4
    }
  ]
}

To run above file use command -:
json-server --watch db.json  --port 3333
To view result
http://localhost:3333/students
get all record
const students = await axios.get("http://localhost:3333/students");
get all single
const student = await axios.get(`http://localhost:3333/students/${id}`);
post
await axios.post(`http://localhost:3333/students`, student);
put
await axios.put(`http://localhost:3333/students/${id}`, student);
delete
await axios.delete(`http://localhost:3333/students/${id}`);
