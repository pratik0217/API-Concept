# API ( Apllication Programming Interface )
<img width="733" height="230" alt="Screenshot 2025-08-01 020700" src="https://github.com/user-attachments/assets/e9601505-eb21-4a07-9017-364163db88a9" />

What is API ?

- Application Programming Interface (API).
( API Work as two programming languagae between interface. )
- We need data from DB(Database) when making project.
- But JS can not connect with database.
( JS, JS Library & framework not connected with database because, JS is Cline-Side-Scripting language work on web browsers. )
- So we have API in other langugae as Java, Python, PHP or Node.js etc.
( this language create API and fetch data, API make json data format because Database is Server-side (Java, Python, PHP or Node.js etc work on Server-side).

<img width="1208" height="774" alt="Screenshot 2025-08-01 022544" src="https://github.com/user-attachments/assets/013b9a78-f517-4b29-b184-4bd47e31abd3" />

Shared Data with API 
- We need same data in multiple platform.
- Like Web application, Mobile Application, Windos OS etc.
- So we make API in one language.
- And use same API with all platform.

# Fetch Data from API with get method 
<img width="797" height="281" alt="Screenshot 2025-08-01 022711" src="https://github.com/user-attachments/assets/3328f81d-39bb-422c-a95e-e32c98fe4bb6" />

API Methods 
- GET (get API data)
- POST (Store data)
- PUT/PATCH (Updating data)
- DELETE (Deleting data)

Test API 
- POSTMAN
- VS Code (Extension Thunder client)

Integrate API & Display Data

- Create function as getApiData().
- function inside store API in url name variable.
- Create let response name variable.
- When calling API then use fetch method and return promise.
- response data convert into json format (syntax - response = response.json() ) return promise
- Call once time in Browser using useEffect().
- get API data store in State.
- And console.log(state) for checking API working properly.
- API data render on UI using Map.

# JSON Server
<img width="704" height="303" alt="Screenshot 2025-08-03 211346" src="https://github.com/user-attachments/assets/92a7b915-9a05-494d-b42a-16966e4106d6" />
Install JSON server 

Following Step for Installation
- npm install json-server
- create db.json
- run the db.json file ( syntax - npx json-server db.json ).
- API test on the thounder clinet.
- create own API like users in db.json
<img width="1156" height="781" alt="Screenshot 2025-08-03 235822" src="https://github.com/user-attachments/assets/52a1689d-8e56-4ad6-9b10-eee7e1e4b6b0" />

- then testing create own API in thounder client.
<img width="776" height="340" alt="Screenshot 2025-08-04 000027" src="https://github.com/user-attachments/assets/e3adc3db-a665-4a51-8254-2f4c683c5673" />

# Intergrate JSON Server API & POST method API 
- This chapter like mini-project.
- Create navigation for Home and user add.
- Using Routes, route and aslo app function wrap in a BrowserRouter.
- make inpur for add user on list.
- added user show on UI.

Integrate Post Method API 
- New user add and store using POST Method.
- show final UI.

Code - 

<img width="1353" height="806" alt="Screenshot 2025-08-04 021134" src="https://github.com/user-attachments/assets/44aeb0ce-ae8b-440d-8759-f3787adf3221" />

<img width="1330" height="907" alt="Screenshot 2025-08-04 021203" src="https://github.com/user-attachments/assets/6cd52e2f-c3e5-43e4-9617-20725083e64b" />

<img width="1329" height="439" alt="Screenshot 2025-08-04 021223" src="https://github.com/user-attachments/assets/4f9837ac-9e5f-4c0f-b8ee-ce010e9b5866" />

<img width="1842" height="910" alt="Screenshot 2025-08-04 021342" src="https://github.com/user-attachments/assets/b1827cf4-5f44-43c1-b694-10be97c71f28" />

<img width="1844" height="395" alt="Screenshot 2025-08-04 021405" src="https://github.com/user-attachments/assets/f96d6f8a-6757-4a5d-aa43-b1293849f250" />

<img width="781" height="915" alt="Screenshot 2025-08-04 021642" src="https://github.com/user-attachments/assets/4a149d39-23ac-4ed9-acbc-18c28c1312f2" />

<img width="769" height="825" alt="Screenshot 2025-08-04 021708" src="https://github.com/user-attachments/assets/a6f066ba-feb9-438f-8d79-1418eb572629" />

<img width="780" height="178" alt="Screenshot 2025-08-04 021723" src="https://github.com/user-attachments/assets/51c6c855-eb67-4b6f-ba18-cb4e42682106" />

UI 
<img width="1919" height="969" alt="Screenshot 2025-08-04 021934" src="https://github.com/user-attachments/assets/743734a1-a030-4d49-9bd8-f1cf07313782" />

<img width="1919" height="909" alt="Screenshot 2025-08-04 022108" src="https://github.com/user-attachments/assets/dfe5c372-8ca2-4385-9a6f-0168648066d3" />

<img width="1919" height="552" alt="Screenshot 2025-08-04 022132" src="https://github.com/user-attachments/assets/5a80f307-e7af-4c2f-84cd-6a323b6c809d" />

<img width="1919" height="40" alt="Screenshot 2025-08-04 022215" src="https://github.com/user-attachments/assets/200bba6b-e593-4090-bea6-6e40a1b479ba" />

# Integrate API for delete Method 
<img width="783" height="264" alt="Screenshot 2025-08-04 022547" src="https://github.com/user-attachments/assets/f36d147c-03f6-4640-9f95-fa0a0b04411f" />

- Already existed user data delete using Delete method.
- Delete method declare with API id then successfully work it.

<img width="1535" height="492" alt="Screenshot 2025-08-04 024152" src="https://github.com/user-attachments/assets/c3caccb6-7f4d-4619-bf93-c176f0d8c91f" />

<img width="1537" height="854" alt="Screenshot 2025-08-04 024215" src="https://github.com/user-attachments/assets/4b54db9d-4194-4464-ba01-661a5ec5f8b6" />

UI 

<img width="1899" height="910" alt="Screenshot 2025-08-04 024444" src="https://github.com/user-attachments/assets/6745f6d1-e429-4333-91c5-e44a10b18ed5" />

<img width="1902" height="807" alt="Screenshot 2025-08-04 024504" src="https://github.com/user-attachments/assets/60632951-9726-4dfa-890f-017e8895990c" />

<img width="1900" height="832" alt="Screenshot 2025-08-04 024526" src="https://github.com/user-attachments/assets/1025762e-96bf-4327-a221-05d884e4d951" />
