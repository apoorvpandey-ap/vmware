# vmware
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



