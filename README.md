<div class="bunga-mawar"></div>
.bunga-mawar {
  width: 200px;
  height: 200px;
  position: relative;
}

.kelopak {
  position: absolute;
  background-color: #F00; /* Merah */
  border-radius: 50%;
  animation: mekar 2s infinite alternate;
}

.kelopak:nth-child(1) {
  width: 80px;
  height: 80px;
  top: 20px;
  left: 60px;
}

.kelopak:nth-child(2) {
  width: 100px;
  height: 100px;
  top: 40px;
  left: 40px;
}

.kelopak:nth-child(3) {
  width: 60px;
  height: 60px;
  top: 60px;
  left: 60px;
}

/* Kelopak lainnya, atur posisi sesuai keinginan */

@keyframes mekar {
  0% {
    transform: scale(0.5);
  }
  100% {
    transform: scale(1);
  }
}
