.bunga {
  width: 100px;
  height: 100px;
  background-color: pink;
  border-radius: 50%;
  position: relative;
}

.kelopak {
  width: 50px;
  height: 50px;
  background-color: lightpink;
  position: absolute;
  border-radius: 50%;
}

.kelopak:nth-child(1) {
  top: 25px;
  left: 0;
}

.kelopak:nth-child(2) {
  top: 0;
  left: 25px;
}

.kelopak:nth-child(3) {
  top: 25px;
  right: 0;
}

.kelopak:nth-child(4) {
  bottom: 0;
  left: 25px;
}
