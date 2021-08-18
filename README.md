![Vmware-logo](https://user-images.githubusercontent.com/66588814/129449988-a7b2b9bf-c360-4df3-9faa-9eeee2dd763d.png)
### ![80](https://user-images.githubusercontent.com/66588814/129146953-ae3b9e00-b4c8-4104-8dbe-f4652ec494bf.png)
## Code Commit Processs{ Diagram 1 }
![19](https://user-images.githubusercontent.com/66588814/129146617-9b9f4206-6eaf-4dca-a808-923bb718fcbd.PNG)

```js
graph LR
    A[master]-.->B;
    A-->G[branch]
    B[1. Import file]-.->C;
    C[2. Edit file]-.->D;
    D[3. Get token number]-.->E;
    E[4. Permission Required from Group]-.->F
    F[5. Submit]-.->G
```

## Code Commit Processs{ Diagram 2 }
![vmware provcess](https://user-images.githubusercontent.com/66588814/129449893-6e1dd3ed-c15f-471f-910b-3329fdbd36c3.PNG)

```js
graph LR
    0[master]-.->1;
    0-->6[branch]
    1[1. Import file]-.->1.5;
    1.5[1.5 Unlock file ]-->2
    2[2. Edit file]-->3;
    3[3. Get token number]-->4;
    4[4. Permission Required from Group]-.->5
    4-.->|suggetions|2
    2-.->|adopting suggetions|4 
    5[5. Submit]-.->6
```
## Code Commit Processs{ Diagram 3 }
![saad](https://user-images.githubusercontent.com/66588814/129945064-6b8c08d9-911c-4bc3-baf8-c0bd4fce5a7a.JPG)

```js
classDiagram
      Bugzilla -- |> Perforce_Table
      Perforce_Table -- |> Build_Table
      Perforce_Table < ..  > Review_Board
      Bugzilla : ID
      Bugzilla : B - 456()
      class Perforce_Table{
            Change_List_No 786
            Bugzilla_No 456()
        }

       class Build_Table{
            SB_ID 
            CLN 456()
        }
        
       class Review_Board{
            ID 123
            Perforce_ID-786)
        }
```

