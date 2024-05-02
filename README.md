<style>
  * {
  padding: 0;
  margin: 0;

  box-sizing: border-box;

  font-family: "Baloo Bhai 2", cursive;
}
nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 2rem;

  background-color: #262626;

  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  z-index: 9999;
  overflow: hidden;
}
/* #navbar{
position:fixed;
top:0;
left:0;
} */

ul {
  display: flex;
  list-style: none;
  /* text-align: center; */
  color: #fff;
  gap: 2rem;
  position: fixed;
  right: 0;
  padding-right: 15px;
}
nav a {
  color: white;
  text-decoration: none;
}
a:hover {
  background-color: rgb(22, 22, 94);
  border-radius: 10px;
  padding: 10px;
}
.logo {
  justify-content: flex-start;
  align-items: flex-start;
  font-size: 2rem;
  color: #fff;

  margin-right: 700px;
}
.btn {
  margin-top: 30px;

  color: white;
  cursor: pointer;
  border-radius: 25px;
  padding: 1rem 2rem;
}

img {
  width: 100%;

  object-fit: cover;
  object-position: center;
}
header {
  background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.2)),
    url(https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2Z2ZXM0cWl0ZzRoZmNkcndmamZidnAyMGE4M2x5dmJwODhjMDhjaCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3o6Ztq1YD8lONQGdck/giphy.gif);
  background-position: center;
  background-size: cover;

  height: 100vh;
}
#home {
  display: flex;

  text-align: center;
  flex-direction: column;
  padding: 220px 200px;
  color: #fff;
  justify-content: center;
  align-items: center;

  text-align: center;
}
.overlay {
  background: rgb(0, 0, 0, -5);
  height: 100vh;
}
#mobile {
  display: none;
  height: 70px;
  line-height: 40px;
  /* background-color: rgba(0, 0, 0, 0.200); */
  background-color: #262626;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  z-index: 9999;
  overflow: hidden;
}

#mobile ul li {
  justify-content: flex-end;
  padding: -25px 5px;
  margin: -38px 0;
  font-size: 1rem;
  color: white;
}
#mobile ul li a {
  display: flex;
  text-decoration: none;
  color: white;
}
@media screen and (max-width: 768px) {
  #mobile {
    display: block;
  }
  #navbar {
    display: none;
  }
  #home {
    display: flex;

    margin-top: 20px;

    text-align: center;

    color: #fff;
    justify-content: center;
    align-items: center;

    text-align: center;
  }

  .logo1 {
    justify-content: flex-start;
    align-items: flex-start;
    font-size: 1.8rem;
    color: #fff;

    margin-left: 20px;
    margin-right: 500px;
    margin-top: 15px;
  }
  a:hover {
    background-color: rgb(22, 22, 94);
    border-radius: 16px;
    padding: 6px 8px 6px 8px;
    margin: -7px;
  }
  header {
    background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.2)),
      url(https://images.unsplash.com/photo-1589302168068-964664d93dc0?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1887&q=80);
    background-position: center;
    background-size: cover;

    height: 180vh;
  }
}
.title {
  text-align: center;
  width: 100%;
  color: yellow;
}

#menu {
  padding: 0;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  grid-gap: 20px 40px;
  background: rgb(245, 242, 242);
  min-height: 100vh;
  /* margin-bottom: 20px; */
}
.heading {
  background: rgb(245, 242, 242);
  color: #373333;
  margin-bottom: 30px;
  padding: 60px 0 30px 0;
  grid-column: 1/-1;
  text-align: center;
}
.heading > h3 {
  font-weight: 600;
  font-size: 22px;
  letter-spacing: 5px;
}
.card {
  display: grid;
  position: relative;
  grid-template-rows: auto 1fr;
  border-radius: 15px;
  box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
  margin: 10px 20px;
}

.card img {
  position: relative;
  width: 100%;
  height: 50vh;
  border-radius: 15px 15px 0 0;
}

.details {
  padding: 20px 10px;
  display: grid;
  grid-template-rows: auto 1fr 50px;
  grid-row-gap: 15px;
}
.details-sub {
  display: grid;
  grid-template-columns: auto auto;
}
.details-sub h5 {
  font-weight: 600;
  font-size: 18px;
}
.price {
  text-align: right;
}
.details p {
  color: #6f6f6f;
  font-size: 15px;
  line-height: 25px;
  align-self: stretch;
}
.details button {
  /* background-color: #cb202d; */
  border: none;
  color: #ffffff;
  font-size: 16px;
  font-weight: 600;
  border-radius: 7px;
  width: 180px;
}

#about {
  padding: 25px 0;
}
.about_row {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  padding: 0 100px;
}
.about_column {
  flex: 1;
}
#btn1 {
  margin-top: 20px;
  padding: 10px 10px;
  border-radius: 15px;
}
.about_column img {
  width: 500px;
  height: 500px;
  border-radius: 50%;
  object-fit: fill;
  margin: auto;
}
.title {
  color: #373333;
  margin-bottom: 30px;
  padding: 50px 0 30px 0;
  text-align: center;
}

#order {
  background: rgb(245, 242, 242);
  color: white;
  min-height: 100vh;
}
.title1 {
  color: #373333;
  margin-bottom: 30px;
  padding: 50px 0 30px 0;
  text-align: center;
}
form {
  width: 450px;
  background-color: white;

  box-shadow: 0 0 20px 0 rgb(213, 212, 210);
  margin: auto;
  margin-top: -20px;
  margin-bottom: 10px;
  border-radius: 20px;
}
.inp_box {
  width: 350px;
  height: 37px;
  /* margin-top: 20px; */
  margin: 25px 45px 0 45px;

  padding: 0 10px;
  border-radius: 14px;
  border: 1px solid #777;
  outline: none;
}
.text_area {
  height: 160px;
  padding-top: 10px;
}
.btn2 {
  border-radius: 20px;
  margin: 20px 45px;
  padding: 0 10px;
  /* margin: auto; */
  width: 30%;
}

textarea {
  height: 150px;
  padding-top: 10px;
}
.btn2 {
  border-radius: 15px;
  color: #fff;
  margin-top: 18px;
  padding: 10px;
}
button {
  background-color: rgb(22, 22, 94);
  color: white;
  border: none;
  cursor: pointer;
}
button:hover {
  background-color: rgb(94, 158, 61);
}
footer {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 1rem 2rem;
  width: 100%;
  background-color: #262626;
  color: white;
}
#menu {
  padding: 0;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  grid-gap: 20px 40px;
  background: rgb(245, 242, 242);
  min-height: 100vh;
  /* margin-bottom: 20px; */
}
.heading {
  background: rgb(245, 242, 242);
  color: #373333;
  margin-bottom: 30px;
  padding: 60px 0 30px 0;
  grid-column: 1/-1;
  text-align: center;
}
.heading > h3 {
  font-weight: 600;
  font-size: 22px;
  letter-spacing: 5px;
}
.card {
  display: grid;
  position: relative;
  grid-template-rows: auto 1fr;
  border-radius: 15px;
  box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
  margin: 10px 20px;
}

.card img {
  position: relative;
  width: 100%;
  height: 50vh;
  border-radius: 15px 15px 0 0;
}

.details {
  padding: 20px 10px;
  display: grid;
  grid-template-rows: auto 1fr 50px;
  grid-row-gap: 15px;
}
.details-sub {
  display: grid;
  grid-template-columns: auto auto;
}
.details-sub h5 {
  font-weight: 600;
  font-size: 18px;
}
.price {
  text-align: right;
}
.details p {
  color: #6f6f6f;
  font-size: 15px;
  line-height: 25px;
  align-self: stretch;
}
.details button {
  /* background-color: #cb202d; */
  border: none;
  color: #ffffff;
  font-size: 16px;
  font-weight: 600;
  border-radius: 7px;
  width: 180px;
}
#about {
  padding: 25px 0;
}
.about_row {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  padding: 0 100px;
}
.about_column {
  flex: 1;
}
#btn1 {
  margin-top: 20px;
  padding: 10px 10px;
  border-radius: 15px;
}
.about_column img {
  width: 500px;
  height: 500px;
  border-radius: 50%;
  object-fit: fill;
  margin: auto;
}
.title {
  color: #373333;
  margin-bottom: 30px;
  padding: 50px 0 30px 0;
  text-align: center;
}

#order {
  background: rgb(245, 242, 242);
  color: white;
  min-height: 100vh;
}
.title1 {
  color: #373333;
  margin-bottom: 30px;
  padding: 50px 0 30px 0;
  text-align: center;
}
form {
  width: 450px;
  background-color: white;

  box-shadow: 0 0 20px 0 rgb(213, 212, 210);
  margin: auto;
  margin-top: -20px;
  margin-bottom: 10px;
  border-radius: 20px;
}
.inp_box {
  width: 350px;
  height: 37px;
  /* margin-top: 20px; */
  margin: 25px 45px 0 45px;

  padding: 0 10px;
  border-radius: 14px;
  border: 1px solid #777;
  outline: none;
}
.text_area {
  height: 160px;
  padding-top: 10px;
}
.btn2 {
  border-radius: 20px;
  margin: 20px 45px;
  padding: 0 10px;
  /* margin: auto; */
  width: 30%;
}

textarea {
  height: 150px;
  padding-top: 10px;
}
.btn2 {
  border-radius: 15px;
  color: #fff;
  margin-top: 18px;
  padding: 10px;
}
button {
  background-color: rgb(22, 22, 94);
  color: white;
  border: none;
  cursor: pointer;
}
button:hover {
  background-color: rgb(94, 158, 61);
}
footer {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 1rem 2rem;
  width: 100%;
  background-color: #262626;
  color: white;
}
</style># Restarant-landing-page
