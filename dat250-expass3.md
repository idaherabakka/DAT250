Technical problems that you encountered during installation and use of MongoDB and how you resolved
- installation went smoothly, but i could not open the exe-file via termial, så i had to run it via file explorer.
- error when checking sha. did not add the whole content for the .sha file so the sha verification didn not work until i fixed the file name and content

Screenshots for:

- The correct validation of the installation package

<img width="869" alt="sha - True" src="https://user-images.githubusercontent.com/97961839/191324314-cb6a24b1-9296-4f68-afaa-8b9fe0d09768.png">

- Relevant results obtained during Experiment 1 (it is not necessary to put a single screenshot on each substep, but at least one significant from each CRUD operation).
  - INSERT
  - <img width="676" alt="image" src="https://user-images.githubusercontent.com/97961839/191328984-ba8ef8c8-8bf7-4aad-8b87-0d1a3cf3a296.png">
  - Query
  - <img width="674" alt="image" src="https://user-images.githubusercontent.com/97961839/191339361-8e0292a9-0123-4c81-8037-4b0ade4ae3d2.png">
  - Update
  - <img width="674" alt="image" src="https://user-images.githubusercontent.com/97961839/191344085-670919e5-1597-425a-9766-aa824c651aff.png">
  - DELETE
  - <img width="426" alt="image" src="https://user-images.githubusercontent.com/97961839/191344396-d0183890-02da-4295-9a3a-7ab553618db1.png">
  - Bulk Write 
  - <img width="679" alt="image" src="https://user-images.githubusercontent.com/97961839/191347428-42c287a6-c210-4b2a-aff6-938b928e52e0.png">

- Experiment 2 example working and the additional Map-reduce operation (and its result) developed by each of you.
  - <img width="566" alt="image" src="https://user-images.githubusercontent.com/97961839/191469013-d157cb70-4f3f-4377-9da4-b9314e50ddcf.png">
  - Map-reduce operation
  - <img width="672" alt="image" src="https://user-images.githubusercontent.com/97961839/191956503-d5df6cab-4747-4a4e-a430-2717c102dc26.png">
  - <img width="675" alt="image" src="https://user-images.githubusercontent.com/97961839/191956616-943f1711-9259-43ec-b9a8-c8d95b40d29a.png">
  - <img width="352" alt="image" src="https://user-images.githubusercontent.com/97961839/191956689-e24c3148-b54d-49de-b5b9-49cbc6769d32.png">

Reason about why your implemented Map-reduce operation in Experiment 2 is useful and interpret the collection obtained.
- can reduce the amount of information, it gets short and no extra uneccessary information. It is great if you are only intrested in some data, e.g. if you want to know how many books are in each library and you dont need any information about what books or how many of each book there are.

Any pending issues with this assignment which you did not manage to solve
- No
