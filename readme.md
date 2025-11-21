<!DOCTYPE <html
</html>

<head
  <link> rel="stylesheet" href="styles/styles.css">
  <title>My First HTML Page</title>
  </Link>

</head>
    <h1>Nemo Hallamaki</h1>
    <p>Hello! I am Nemo who loves fantasy novels and games.</p>
    <img src="images/IMG_6295.png" alt="Nemo" width="200">
  </head>
  <!-- Task 2: Lists of Hobbies -->
  <h2>My Hobbies (Ordered List)</h2>
  <ol>
    <li>Reading</li>
    <li>Gaming</li>
    <li>Gym</li>
  </ol>

  <h2>My Hobbies (Unordered List)</h2>
  <ul>
    <li>Cooking</li>
    <li>Boxin</li>
    <li>Wrestling</li>
  </ul>

  <!-- Task 3: Hyperlink -->
  <p>Check out my favorite website: <a href="https://www.youtube.com" target="_blank">Visit Youtube</a></p>

  <!-- Task 4: Table and Form -->
  <h2>My Ongoing Courses</h2>
  <table>
p {
    color: rgb(133, 38, 227);
}

body {
    background-color: rgba(66, 180, 169, 0);
}

h1 {
    color: blueviolet;
    font-size: 3em;
}

div {
    padding: 30px;
    margin: 15px;
}

table {
    width: 90%;
    border-collapse: collapse;
}

th,
td {
    border: 2px solid #ddd;
    padding: 10px;
    text-align: left;
}

th {
    background-color: grey;
}

form {
    display: flex;
    flex-direction: column;
    gap: 10px;
}

label {
    font-weight: bolder;
}

input[type="text"],
input[type="email"] {
    padding: 10px;
    border: 2px solid #ddd;
    border-radius: 5px;
}

input[type="submit"] {
    background-color: #767679;
    color: rgb(72, 70, 70);
    padding: 10px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

input[type="submit"]:hover {
    background-color: #1c4f5c;
}

p {
    color: rgb(43, 192, 160);
}

body {
    background-color: rgb(72, 70, 70)
}


div {
    padding: 30px;
    margin: 15px;
}

table {
    width: 90%;
    border-collapse: collapse;
}

th,
td {
    border: 2px solid #b26d6d;
    padding: 10px;
    text-align: left;
}

th {
    background-color: grey;
}

form {
    display: flex;
    flex-direction: column;
    gap: 10px;
}

label {
    font-weight: bolder;
}

input[type="text"],
input[type="email"] {
    padding: 10px;
    border: 2px solid #915050;
    border-radius: 5px;
}

input[type="submit"] {
    background-color: #767679;
    color: rgb(72, 70, 70);
    padding: 10px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

input[type="submit"]:hover {
    background-color: #5e5f5e;
}

.transition-button {
    background-color: rgb(100, 188, 217);
    padding: 40px 50px;
    border: none;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.transition-button:hover {
    background-color: rgb(234, 104, 104);
}

.animation-box {
        width: 50px;
        height: 50px;
        background-color: lightgreen;
        position: relative;
        animation: move 2s infinite alternate;
      }
      
      @keyframes move {
        from {
          left: 0;
        }
        to {
          left: 100px;
        }
      }

.pseudo-list li:nth-child(odd) {
    background-color: rgb(56, 142, 145);
}

.pseudo-list li:nth-child(even) {
    background-color: rgb(47, 16, 49);
}

.filter-image {
    filter: grayscale(100%);
    transition: filter 0.2s ease;
}

.filter-image:hover {
    filter: grayscale(20%);
}

.quote {
    content: 'Elämä on Lifee';
    position: relative;
    padding-left: 20px;
    font-style: oblique;
}

.quote::before {
    content: 'Elämä on Lifee';
    font-size: 40px;
    position: absolute;
    left: 0;
    top: 0;
    color: rgb(13, 204, 191);
}

.filter-image {
    filter: grayscale(100%);
    transition: filter 0.3s ease;
}

.filter-image:hover {
    filter: grayscale(0%);
}

.flex-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

  
  .box {
    background-color: rgb(10, 53, 67);
    padding: 40px;
    text-align: center;
  }

  .grid-container {
    display: grid;
    grid-template-columns: repeat(3, 2fr);
    grid-gap: 20px;
  }
  
  .grid-item {
    background-color: rgb(110, 80, 194);
    padding: 35px;
    text-align: center;
  }

  .responsive-box {
    padding: 35px;
    text-align: center;
  }
  
  @media (max-width: 500px) {
    .responsive-box {
      background-color: rgb(52, 126, 109);
    }
  }
  
  @media (min-width: 301px) {
    .responsive-box {
      background-color: rgb(122, 33, 163);
    }
  }
