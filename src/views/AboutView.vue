<template>
  <div class="w3-container text-black">

        <div class="w3-row">

            <a href="javascript:void(0)" onclick="openModule(event, 'mod1');">
                <div class="w3-half tablink w3-bottombar w3-hover-light-grey w3-padding w3-rubik">Module 1</div>
            </a>

            <a href="javascript:void(0)" onclick="openModule(event, 'mod2');">
                <div class="w3-half tablink w3-bottombar w3-hover-light-grey w3-padding w3-rubik">Module 2</div>
            </a>

        </div>

        <div id="mod1" class="w3-container module" style="display:none">

            <div id="less1">

                <div id="navbar" class="w3-bar w3-border w3-card-4 w3-light-grey">
                    <a href="#mod1less1" class="w3-bar-item w3-button">Lesson 1</a>
                    <a href="#mod1less2" class="w3-bar-item w3-button">Lesson 2</a>
                    <a href="#mod1less3" class="w3-bar-item w3-button">Lesson 3</a>
                </div>

                <hr>

                <a class="w3-rubik theme" name="mod1less1">Lesson 1</a>

                <p class="w3-rubik main">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Maxime suscipit,
                    placeat dignissimos laboriosam aspernatur est iure expedita architecto error commodi dolorum nostrum
                    animi inventore vitae officiis et doloremque explicabo cumque laudantium recusandae sed? Tenetur
                    quidem sed architecto commodi amet accusamus aut doloribus impedit, eos beatae ratione corrupti ut
                    sit illo.</p>

                <p class="w3-rubik main">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Animi, consequuntur.
                    Provident accusamus vel omnis eaque iste ut. Optio similique quas perspiciatis? Aperiam ipsum eius
                    eos consequuntur fugit cumque ratione sit veniam, optio assumenda, quam culpa.</p>

                <div class="w3-panel w3-pale-green w3-border">
                    <h3>Lorem, ipsum.</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem, vel.</p>
                </div>

                <p class="w3-rubik main">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ullam ratione,
                    ducimus, consequatur quas omnis voluptatum architecto minus eius maiores mollitia quos eum
                    voluptate. A fugiat porro mollitia consequatur amet sequi.</p>

                <hr>

                <div class="video">
                    <iframe width="1000" height="650" src="https://www.youtube.com/embed/CHSnz0bCaUk" title="Alaska"
                        frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen></iframe>
                </div>

                <hr>

            </div>

            <div id="less2">
                <a class="w3-rubik theme" name="mod1less2">Lesson 2</a>

                <p class="w3-rubik main">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Maxime suscipit,
                    placeat dignissimos laboriosam aspernatur est iure expedita architecto error commodi dolorum nostrum
                    animi inventore vitae officiis et doloremque explicabo cumque laudantium recusandae sed? Tenetur
                    quidem sed architecto commodi amet accusamus aut doloribus impedit, eos beatae ratione corrupti ut
                    sit illo.</p>

                <p class="w3-rubik main">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Animi, consequuntur.
                    Provident accusamus vel omnis eaque iste ut. Optio similique quas perspiciatis? Aperiam ipsum eius
                    eos consequuntur fugit cumque ratione sit veniam, optio assumenda, quam culpa.</p>

                <p class="w3-rubik main">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ullam ratione,
                    ducimus, consequatur quas omnis voluptatum architecto minus eius maiores mollitia quos eum
                    voluptate. A fugiat porro mollitia consequatur amet sequi.</p>

                <button onclick="myFunction('acc1')" class="w3-button w3-block w3-black w3-left-align">
                    <h1 class="w3-rubik main">Accordion 1</h1>
                </button>
                <div id="acc1" class="w3-hide w3-border">
                    <ul class="w3-ul w3-rubik main">
                        <li>Lorem ipsum dolor sit amet.</li>
                        <li>Lorem ipsum dolor sit amet consectetur.</li>
                        <li>Lorem ipsum dolor sit amet consectetur adipisicing.</li>
                    </ul>
                </div>

                <hr>

                <div class="video">
                    <iframe width="1000" height="650" src="https://www.youtube.com/embed/CHSnz0bCaUk" title="Alaska"
                        frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen></iframe>
                </div>

                <hr>

            </div>

            <div id="less3">
                <a class="w3-rubik theme" name="mod1less3">Lesson 3</a>

                <p class="w3-rubik main">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Maxime suscipit,
                    placeat dignissimos laboriosam aspernatur est iure expedita architecto error commodi dolorum nostrum
                    animi inventore vitae officiis et doloremque explicabo cumque laudantium recusandae sed? Tenetur
                    quidem sed architecto commodi amet accusamus aut doloribus impedit, eos beatae ratione corrupti ut
                    sit illo.</p>

                <p class="w3-rubik main">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Animi, consequuntur.
                    Provident accusamus vel omnis eaque iste ut. Optio similique quas perspiciatis? Aperiam ipsum eius
                    eos consequuntur fugit cumque ratione sit veniam, optio assumenda, quam culpa.</p>

                <p class="w3-rubik main">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ullam ratione,
                    ducimus, consequatur quas omnis voluptatum architecto minus eius maiores mollitia quos eum
                    voluptate. A fugiat porro mollitia consequatur amet sequi.</p>

                <hr>

                <div class="video">
                    <iframe width="1000" height="650" src="https://www.youtube.com/embed/CHSnz0bCaUk" title="Alaska"
                        frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen></iframe>
                </div>

                <hr>

            </div>

        </div>

        <div id="mod2" class="w3-container module" style="display:none">

            <div id="less1">

                <div id="navbar" class="w3-bar w3-border w3-card-4 w3-light-grey">
                    <a href="#mod2less1" class="w3-bar-item w3-button">Lesson 1</a>
                    <a href="#mod2less2" class="w3-bar-item w3-button">Lesson 2</a>
                    <a href="#mod2less3" class="w3-bar-item w3-button">Lesson 3</a>
                </div>

                <hr>

                <a class="w3-rubik theme" name="mod2less1">Lesson 1</a>

                <p class="w3-rubik main">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Maxime suscipit,
                    placeat dignissimos laboriosam aspernatur est iure expedita architecto error commodi dolorum nostrum
                    animi inventore vitae officiis et doloremque explicabo cumque laudantium recusandae sed? Tenetur
                    quidem sed architecto commodi amet accusamus aut doloribus impedit, eos beatae ratione corrupti ut
                    sit illo.</p>

                <p class="w3-rubik main">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Animi, consequuntur.
                    Provident accusamus vel omnis eaque iste ut. Optio similique quas perspiciatis? Aperiam ipsum eius
                    eos consequuntur fugit cumque ratione sit veniam, optio assumenda, quam culpa.</p>

                <div class="w3-panel w3-pale-green w3-border">
                    <h3>Lorem, ipsum.</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem, vel.</p>
                </div>

                <p class="w3-rubik main">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ullam ratione,
                    ducimus, consequatur quas omnis voluptatum architecto minus eius maiores mollitia quos eum
                    voluptate. A fugiat porro mollitia consequatur amet sequi.</p>

                <hr>

                <div class="video">
                    <iframe width="1000" height="650" src="https://www.youtube.com/embed/CHSnz0bCaUk" title="Alaska"
                        frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen></iframe>
                </div>

                <hr>

            </div>

            <div id="less2">
                <a class="w3-rubik theme" name="mod2less2">Lesson 2</a>

                <p class="w3-rubik main">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Maxime suscipit,
                    placeat dignissimos laboriosam aspernatur est iure expedita architecto error commodi dolorum nostrum
                    animi inventore vitae officiis et doloremque explicabo cumque laudantium recusandae sed? Tenetur
                    quidem sed architecto commodi amet accusamus aut doloribus impedit, eos beatae ratione corrupti ut
                    sit illo.</p>

                <p class="w3-rubik main">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Animi, consequuntur.
                    Provident accusamus vel omnis eaque iste ut. Optio similique quas perspiciatis? Aperiam ipsum eius
                    eos consequuntur fugit cumque ratione sit veniam, optio assumenda, quam culpa.</p>

                <p class="w3-rubik main">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ullam ratione,
                    ducimus, consequatur quas omnis voluptatum architecto minus eius maiores mollitia quos eum
                    voluptate. A fugiat porro mollitia consequatur amet sequi.</p>

                <button onclick="myFunction('acc2')" class="w3-button w3-block w3-black w3-left-align">
                    <h1 class="w3-rubik main">Accordion 1</h1>
                </button>
                <div id="acc2" class="w3-hide w3-border">
                    <ul class="w3-ul w3-rubik main">
                        <li>Lorem ipsum dolor sit amet.</li>
                        <li>Lorem ipsum dolor sit amet consectetur.</li>
                        <li>Lorem ipsum dolor sit amet consectetur adipisicing.</li>
                    </ul>
                </div>

                <hr>

                <div class="video">
                    <iframe width="1000" height="650" src="https://www.youtube.com/embed/CHSnz0bCaUk" title="Alaska"
                        frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen></iframe>
                </div>

                <hr>

            </div>

            <div id="less3">
                <a class="w3-rubik theme" name="mod2less3">Lesson 3</a>

                <p class="w3-rubik main">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Maxime suscipit,
                    placeat dignissimos laboriosam aspernatur est iure expedita architecto error commodi dolorum nostrum
                    animi inventore vitae officiis et doloremque explicabo cumque laudantium recusandae sed? Tenetur
                    quidem sed architecto commodi amet accusamus aut doloribus impedit, eos beatae ratione corrupti ut
                    sit illo.</p>

                <p class="w3-rubik main">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Animi, consequuntur.
                    Provident accusamus vel omnis eaque iste ut. Optio similique quas perspiciatis? Aperiam ipsum eius
                    eos consequuntur fugit cumque ratione sit veniam, optio assumenda, quam culpa.</p>

                <p class="w3-rubik main">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ullam ratione,
                    ducimus, consequatur quas omnis voluptatum architecto minus eius maiores mollitia quos eum
                    voluptate. A fugiat porro mollitia consequatur amet sequi.</p>

                <hr>

                <div class="video">
                    <iframe width="1000" height="650" src="https://www.youtube.com/embed/CHSnz0bCaUk" title="Alaska"
                        frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen></iframe>
                </div>

                <hr>

            </div>

        </div>

    </div>
</template>

<script>
function openModule(evt, moduleName) {
  var i, x, tablinks;
  x = document.getElementsByClassName("module");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < x.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" w3-border-red", "");
  }
  document.getElementById(moduleName).style.display = "block";
  evt.currentTarget.firstElementChild.className += " w3-border-red";
}

function myFunction(id) {
  var x = document.getElementById(id);
  if (x.className.indexOf("w3-show") == -1) {
    x.className += " w3-show";
  } else { 
    x.className = x.className.replace(" w3-show", "");
  }
}
</script>

<style scoped>
.w3-rubik {
  
}

.theme {
    font-weight: 700;
    font-size: 25px;
}

.main {
    font-weight: 500;
    font-size: 20px;
}

.video {
    display: flex;
    justify-content: center;
    align-items: center; 
}

hr{
    border: 1px solid lightgrey;
}

li{
    color: lightgray;
}

body{
    background-color: black;
}
</style>
