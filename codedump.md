* {
  box-sizing: border-box;
}

body {
  width: 100vw;
  height: auto;
  margin: 0px;
  padding: 0px;
  overflow-x: hidden;
  display: flex;
  flex-direction: column;
}
body {
  display: grid;
  grid-template-rows: 750px 668px 888px 333px 632px 237px 298px; /*3806*/
  /*47em 42em 55em 21em 40em 15em 19em*/
  grid-template-columns: 100vw;
  background-size: cover;
  margin: 0;
  /* width: auto; */
}

.title {
  background-image: url("imports/rectangle-9fea.jpg");
  background-color: blue;
  background-position: center;
  background-size: cover;
  width: 100vw;
  grid-row: 1;
  grid-column: 1;
  justify-content: space-between;
}
nav {
  padding-right: 0;
  height: auto;
  width: 100vw;
  align-content: center;
  justify-content: space-between;
  padding: 2em;
  display: flex;
}
ul {
  list-style-type: none;
  /* margin-top: 2em; */
  align-items: center;
  justify-content: flex-end;
  justify-self: flex-end;
  display: inline;
  float: right;
}
li {
  display: inline;
  text-align: right;
  padding: 2em;
  font-family: "Montserrat", sans-serif;
  font-size: 11px;
}

.nipB {
  padding-left: 4em;
  position: aboslute;
  align-self: center;
  margin-top: 2em;
}

.god {
  text-align: center;
  justify-content: center;
  align-self: center;
  align-content: flex-start;
  flex-direction: column;
  width: 100vw;
  height: 75vh;
}

h1 {
  text-align: center;
  font-family: "Playfair display", serif;
  font-size: 80px;
  font-weight: 300;
  margin-top: 12%;
  /* height: 8em; */
  /* margin-bottom: 1em; */
}

.godp {
  font-size: 18px;
  font-family: "Open-sans", sans-serif;
  height: 4em;
  justify-self: center;
  text-align: center;
}
button {
  border-style: none;
  justify-self: center;
  background-image: url("imports/new learn.png");
  background-position: center;
  color: #ffffff;
  font-size: 12px;
  padding: 10px 47px 18px 47px;
  /* margin: 50px; */
  border-radius: 24px 24px 24px;
}
.about {
  grid-row: 2;
  grid-column: 1;
  background-color: #f3f7f8;
  grid-template-columns: repeat(auto-fit, minmax(50%, 1fr));
  display: grid;
  /* display: flex; */
  /* grid-template-columns: 1fr 1fr; */
  /* grid-template-rows: auto; */
}

h4 {
  font-family: "Montserrat", sans-serif;
  font-size: 33px;
  font-weight: bolder;
}

.usL {
  font-family: "Playfair display", serif;
  font-size: 20px;
  color: #95989a;
  /* flex-direction: row; */
  box-sizing: border-box;
}

.usS {
  font-family: "Open Sans";
  font-size: 14px;
  color: #95989a;
  box-sizing: border-box;
  line-height: 1.5;
}
.aboutus {
  text-align: left;
  grid-column: 1;
  word-wrap: normal;
  box-sizing: border-box;
  margin: auto 2% auto 10%;
  align-items: stretch;
  /* display: flex; */
  /* flex-direction: column; */
}

.hand {
  background-image: url("imports/group-20hand.jpg");
  background-size: contain;
  background-repeat: no-repeat;
  background-position: center;
  /* display: flex; */
  height: 515px;
  /* width: auto; */
  /* justify-content: flex-end;
  align-self: center;
  align-items: flex-end; */
  padding: 120px 150px 12px auto;
  margin: auto 10% auto 1em;
  grid-column: 2;
}

h6 {
  color: #1005ff;
  font-size: 16px;
  font-family: "Montserrat", serif;
  display: table-cell;
  vertical-align: bottom;
  text-align: center;
}
.buyme {
  align-items: flex-end;
  padding-left: 2%;
  padding-bottom: 0;
  align-self: flex-end;
  margin-top: auto;
  margin-bottom: 10px;
}
.viewmore {
  color: #1d1d1d;
  align-items: flex-start;
  white-space: nowrap;
  /* padding-bottom: 0; */
  /* align-self: flex-end; */
  padding-right: 3%;
  /* display: inline-block; */
  font-family: "Montserrat", sans-serif;
  font-size: 14px;
  /* height: 25px; */
  /* width: 100px; */
}
.arrow {
  margin-left: 2%;
  height: 15px;
}
.producthead {
  width: 100%;
  height: 120px;
  position: relative;
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
  align-self: flex-end;
  margin-bottom: 0;
}

.price {
  color: #666666;
  font-size: 15px;
  font-family: "Open sans";
  display: table-cell;
  vertical-align: bottom;
  text-align: left;
  align-content: flex-end;
}

.products {
  background-color: #ffffff;
  grid-row: 3;
  height: 888px;
  grid-column: 1;
  display: grid;
}

.textbox {
  text-align: left;
  margin-left: 2px;
  margin-bottom: 2px;
  position: relative;
}
.container {
  display: flex;
  padding: 10%;
  /* background-position: center;
  background-size: cover;
  padding-bottom: 122px;
  margin-bottom: 0;
  height: 705px; */
}

.grid {
  grid-template-rows: 50% 50%;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  display: grid;
  grid-gap: 30px 30px;
  align-content: flex-end;
  box-sizing: border-box;
}

.parcel {
  grid-row: 1 / span 2;
  grid-column: 1 / span 2;
  background-color: #f4f4f4;
  display: table-cell;
  vertical-align: bottom;
  background-image: url("imports/pics/redbag.jpg");
  background-position: center;
  background-size: cover;
}

.koo {
  grid-row: 1;
  grid-column: 3;
  background-color: #f4f4f4;
  background-image: url("imports/pics/greenbag.jpg");
  background-position: center;
  background-size: cover;
}

.head {
  grid-row: 2;
  grid-column: 3;
  background-color: #f4f4f4;
  background-image: url("imports/pics/makeup.jpg");
  background-position: center;
  background-size: contain;
}

.scoop {
  grid-row: 1;
  grid-column: 4;
  background-color: #f4f4f4;
  background-image: url("imports/pics/purse.jpg");
  background-size: cover;
  background-position: center;
}

.mari {
  grid-row: 2;
  grid-column: 4;
  background-color: #f4f4f4;
  background-image: url("imports/pics/black.jpg");
  background-position: center;
  background-size: cover;
}

.numberbar {
  grid-row: 4;
  grid-column: 1;
  background-color: #1d1d1d;
  display: flex;
  align-items: center;
  justify-content: space-evenly;
}
.blsquare {
  color: #ffffff;
  font-family: "Playfair display", serif;
  font-size: 18px;
  align-content: center;
  align-items: center;
  line-height: 0.2;
  text-align: center;
}

.number {
  color: #ffffff;
  font-family: "Open sans";
  font-size: 45px;
  font-weight: bold;
  display: inline-flex;
  justify-content: space-around;
  align-items: center;
  align-content: center;
  position: relative;
}

.contact {
  grid-row: 5;
  grid-column: 1;
  background: linear-gradient(to left, #ffffff 50%, #f4f4f4 50%);
  display: grid;
  /* grid-template-rows: auto; */
  grid-template-columns: repeat(auto-fit, minmax(50%, 1fr));
  flex-direction: column;
}

.emptycell {
  grid-row: 1;
  grid-column: 1;
}
.touch {
  display: flex;
  /* justify-content: flex-start; */
  grid-row: 1;
  grid-column: 2;
  height: 20em;

  /* align-items: center; */
  margin: 13% 15% 0 13%;
  padding-bottom: 4em;
  flex-direction: column;
}

.largertext {
  font-family: "Playfair display", serif;
  font-size: 20px;
  color: #666666;
  margin-top: -20px;
}

.smallertext {
  color: #666666;
  font-family: "Open sans";
  font-size: 14px;
}

.inputemail {
  grid-row: 1;
  grid-column: 2;
  margin: auto 15% 30% 13%;
  padding-top: 15px;
  flex-direction: row;
  align-self: flex-end;
  padding-top: 1em;
  height: 48px;
  width: 430px;
  justify-content: center;
}

.email {
  width: 30vw;
  height: 40px;
  padding-left: 10px;
  color: #939393;
  padding-right: 0;
  border-radius: 24px 0px 0px 24px;
  font-family: "Playfair display", serif;
  font-size: 12px;
  border-color: #1d1d1d;
}

.submit {

  height: 40px;
  width: 12vw;
  background: #1005ff;
  color: #ffffff;
  text-align: center;
  padding-left: 0;
  border-radius: 0px 24px 24px 0px;

  font-family: "Montserrat" sans-serif;
  font-size: 12px;
  border: none;
  -webkit-appearance: none;
}
.media {
  grid-row: 6;
  grid-column: 1;
  background-color: #f3f7f8;
  height: 250px;
  justify-content: space-evenly;
  display: flex;
  width: 100vw;
  align-items: center;
}

.medicons {
  display: flex;
  list-style: none;
  align-content: center;
  /* height: 25px; */
  padding-top: 12em;
  padding-bottom: 13em;
  width: 100vw;
  justify-content: space-evenly;
  box-sizing: border-box;
}

.company {
  max-height: 3em;
  justify-content: center;
  align-items: center;
  padding-left: 1px;
  box-sizing: border-box;
}

.bbc {
  max-height: 20px;
}
.netflix {
  max-height: 20px;
}

.mash {
  max-height: 20px;
}

.forbes {
  max-height: 20px;
}

.life {
  max-height: 20px;
}

.buzz {
  max-height: 20px;
}
.address {
  color: #ffffff;
  grid-row: 7;
  grid-column: 1;
  background-color: #1d1d1d;
  align-items: center;
  display: flex;
  justify-content: space-evenly;
  max-height: 300px;
  padding: 75px 75px auto 75px;
  flex-direction: column;
}

.data-align {
  display: flex;
  justify-content: space-evenly;
  align-items: flex-start;
  /* flex-flow: nowrap; */
  justify-items: stretch;
  padding: auto 75px;
  width: 100%;
}

.logo-w {
  margin-left: 75px;
}
.addr {
  font-family: "Open sans" 300;
  font-size: 14px;
  line-height: 1.5;
  background-color: #1d1d1d;
  text-align: left;
}

.phone {
  font-family: "Open sans";
  font-size: 14px;
  line-height: 1.5;
  background-color: #1d1d1d;
  text-align: left;
}

.nipw {
  align-self: flex-start;
  justify-content: flex-end;
  margin-top: 75px;
  justify-content: center;
  max-width: 160px;
}
.copywrite {
  position: relative;

  font-family: "Open sans";
  font-size: 14px;
  margin-bottom: 5px;
  width: 250px;
  height: 20px;
  background-color: #1d1d1d;
  text-align: center;
  margin-top: 0;
  padding-right: 0;
}
