# User Registry

<img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="c#" height="28px"> <img src="https://img.shields.io/badge/.NET8-5C2D91?style=for-the-badge&logo=.net&logoColor=white" alt=".NET8" height="28px"> <img src="https://img.shields.io/badge/Blazor-8a70da?style=for-the-badge&logo=c-sharp&logoColor=white&" alt="Razor Pages" height="28px">

User Registry Web App provides fake user data generation on the fly.\
User can control error count, seed value (used for data generation), and region.\
In addition to that user can download result stored in .csv file. 

The app is build with Blazor and uses WebAssembly to run the data generation.

App uses Bogus library to generate fake data.

The data generates in deterministic manner. Combination of seed, region and error count values drives the generator.\
Therefore as long as the values provided remain the same so does the result.


>Check out the <a href="https://youtu.be/oVIy1iPyh-k"><u><i>Demo Video</a>!</i></u>

---

>You can play with the deployed test version on:\
<a href="https://task5-user-registry.azurewebsites.net">
<u><i>task5-user-registry.azurewebsites.net/</i></u>
</a>

<img src="img/user-registry.png" alt="main-page" width="540">

---

<details>
  <summary><i>Screenshots</i></summary>

<img src="img/csv-export.png" alt="csv-export" width="540">

---

<img src="img/large-data.png" alt="large-data" width="540">

</details>
