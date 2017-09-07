<template>
  <section id="mainWrapper">
    <section id="header">
      <div class="container">
        <div class="row">
          <div class="col-lg-3 col-sm-3 small-text-center logo col-xs-12">
            <a href="index.html"><img src="images/logo.png" alt="" /></a>
          </div>
          <div class="col-lg-6 col-sm-6 small-text-center col-xs-12">
            <form>
              <input type="text" placeholder="What are you searching for?" />
            </form>
          </div>
          <div class="col-lg-3 col-sm-3 small-text-center text-right col-xs-12">
            <p><a href="sign-up.html">Sign up</a><span>|</span><a href="login.html">Log in</a></p>
          </div>
        </div>
      </div>
    </section>
    <section id="product">
      <div class="container">
        <div class="row">
          <div class="border col-xs-12">
            <div class="col-lg-6 first small-text-center col-sm-6 col-xs-12">
              <h3>Buy digital assets for a dollar.</h3>
              <p>34.500 pictures, audio files and videos.</p>
            </div>
            <div class="col-lg-6 small-text-center col-sm-6 space-small select text-right flush col-xs-12">
              <form>
                <p>
                  <span>Show</span>
                  <select>
                    <option>All</option>
                    <option>All</option>
                    <option>All</option>
                  </select>
                  <span class="left">Sort by</span>
                  <select>
                    <option>Type</option>
                    <option>Type</option>
                    <option>Type</option>
                  </select>
                </p>
              </form>
            </div>
            <div class="col-lg-12 stop flush col-xs-12">
              <div class="col-lg-3 col-sm-4 flush col-xs-12">
                <form>
                  <div class="col-xs-12 bottom title">
                    <h3>TYPE</h3>
                    <p>
                      <input type="checkbox" id="test1" />
                      <label for="test1">Pictures <span class="pull-right">143</span></label>
                    </p>
                    <p>
                      <input type="checkbox" id="test2" />
                      <label for="test2">Videos <span class="pull-right">22</span></label>
                    </p>
                    <p>
                      <input type="checkbox" id="test3" />
                      <label for="test3">Audio files <span class="pull-right">11</span></label>
                    </p>
                  </div>
                  <div class="col-xs-12 title">
                    <h3>Categories</h3>
                                    <select id="example-getting-started" name="multiselect[]" multiple="multiple">
                                        <!--<option value="Select All">Select All &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="pull-right">143</span></option>-->
                                        <option value="Architecture">Architecture (<span class="pull-right">55</span>)</option>
                                        <option value="Drawings">Drawings (<span class="pull-right">23</span>)</option>
                                        <option value="Computers">Computers (<span class="pull-right">13</span>)</option>
                                        <option value="Animals">Animals (<span class="pull-right">21</span>)</option>
                                        <option value="Landscapes">Landscapes (<span class="pull-right">11</span>)</option>
                                        <option value="Mockups">Mockups (<span class="pull-right">16</span>)</option>
                                    </select>
                  </div>
                </form>
                <div id="advance" class="col-xs-12 flush">
                  <div id="advance-info" style="display:none;">
                    <div class="col-xs-12 top bottom title">
                      <h3>SIZE</h3>
                      <p>
                        <input type="radio" id="radio01" name="radio" />
                        <label for="radio01"><span></span>Any <em class="pull-right">383</em></label>
                      </p>
                      <p>
                        <input type="radio" id="radio02" name="radio" />
                        <label for="radio02"><span></span>< 100k <em class="pull-right">67</em></label>
                      </p>
                      <p>
                        <input type="radio" id="radio03" name="radio" />
                        <label for="radio03"><span></span>100Kb - 500Kb <em class="pull-right">120</em></label>
                      </p>
                      <p>
                        <input type="radio" id="radio04" name="radio" />
                        <label for="radio04"><span></span>500Kb - 1Mb <em class="pull-right">15</em></label>
                      </p>
                      <p>
                        <input type="radio" id="radio05" name="radio" />
                        <label for="radio05"><span></span>> 1Mb <em class="pull-right">204</em></label>
                      </p>
                    </div>
                    <div class="col-xs-12 bottom small title">
                      <form>
                      <h3>Dimensions</h3>
                      <div class="col-lg-5 flush col-xs-5">
                        <label>Min width</label>
                        <input type="text" />
                      </div>
                      <div class="col-lg-1 text-center flush col-xs-1">
                        <label>&nbsp;</label>
                        <p>to</p>
                      </div>
                      <div class="col-lg-6 flush col-xs-6">
                        <div class="col-lg-9 flush col-xs-9">
                          <label>Max  width</label>
                          <input type="text" />
                        </div>
                        <div class="col-lg-3 flush col-xs-3">
                          <label>&nbsp;</label>
                          <input type="submit" value="Go" />
                        </div>
                      </div>
                      </form>
                      <div class="col-xs-12 flush">
                      <form>
                        <div class="col-lg-5 flush col-xs-5">
                          <label>Min height</label>
                          <input type="text" />
                        </div>
                        <div class="col-lg-1 text-center flush col-xs-1">
                          <label>&nbsp;</label>
                          <p>to</p>
                        </div>
                        <div class="col-lg-6 flush col-xs-6">
                          <div class="col-lg-9 flush col-xs-9">
                            <label>Max  height</label>
                            <input type="text" />
                          </div>
                          <div class="col-lg-3 flush col-xs-3">
                            <label>&nbsp;</label>
                            <input type="submit" value="Go" />
                          </div>
                        </div>
                      </form>
                      </div>
                    </div><!-- -->
                    <div class="col-xs-12 bottom small title">
                      <form>
                        <h3>Length of time</h3>
                        <div class="col-lg-5 flush col-xs-5">
                          <div class="col-lg-12 flush col-xs-12">
                            <label>Min</label>
                          </div>
                          <div class="col-lg-5 flush col-xs-5">
                            <input type="text" />
                          </div>
                          <div class="col-lg-2 text-center flush col-xs-2">
                            <p>:</p>
                          </div>
                          <div class="col-lg-5 flush col-xs-5">
                            <input type="text" />
                          </div>
                        </div>
                        <div class="col-lg-1 text-center flush col-xs-1">
                          <label>&nbsp;</label>
                          <p>to</p>
                        </div>
                        <div class="col-lg-6 flush col-xs-6">
                          <div class="col-lg-12 flush col-xs-12">
                            <label>Max</label>
                          </div>
                          <div class="col-lg-4 flush col-xs-4">
                            <input type="text" />
                          </div>
                          <div class="col-lg-1 text-center flush col-xs-1">
                            <p>:</p>
                          </div>
                          <div class="col-lg-4 flush col-xs-4">
                            <input type="text" />
                          </div>
                          <div class="col-lg-3 flush col-xs-3">
                            <input type="submit" value="Go" />
                          </div>
                        </div>
                      </form>
                    </div><!-- -->
                    <div class="col-xs-12 small title">
                    <form>
                      <h3>asset listing date</h3>
                      <div class="col-lg-5 flush col-xs-5">
                        <input class="date" id="datepicker-one" type="text" />
                      </div>
                      <div class="col-lg-1 text-center flush col-xs-1">
                        <p>to</p>
                      </div>
                      <div class="col-lg-6 flush col-xs-6">
                        <div class="col-lg-9 flush col-xs-9">
                          <input class="date" id="datepicker-two" type="text" />
                        </div>
                        <div class="col-lg-3 flush col-xs-3">
                          <input type="submit" value="Go" />
                        </div>
                      </div>
                    </form>
                    </div>
                  </div>
                  <div class="col-xs-12 top bottom text-center">
                    <a id="show-ad" class="link">Show advanced</a>
                    <a id="hide-ad" class="link" style="display:none;">Hide advanced</a>
                  </div>
                </div>
              </div>
              <div class="col-lg-9 col-sm-8 flush col-xs-12">
                <div class="col-lg-4 col-sm-6 col-xs-12">
                  <div id="first" class="position">
                    <img class="fullwidth" src="images/product-1.png" alt="" />
                    <div class="align"><a class="wishlist"></a></div>
                  </div>
                  <div class="bord">
                    <div class="space col-xs-12">
                      <div class="col-lg-10 col-sm-10 col-xs-10">
                        <h3>Notebook MockUp</h3>
                        <p>by Jonathan Yorkshire</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <a href="#"><img src="images/img-camera.png" alt="" /></a>
                      </div>
                    </div>
                    <div class="bord-small black col-xs-12">
                      <div class="col-lg-4 col-sm-4 border-right col-xs-4">
                        <p>$1.00</p>
                      </div>
                      <div class="col-lg-6 col-sm-6 border-right col-xs-6">
                        <p>124Kb</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <p>
                          <a href="#"><img src="images/img-download.png" alt="" /></a>
                        </p>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-lg-4 col-sm-6 col-xs-12">
                  <div id="second" class="position">
                    <img class="fullwidth" src="images/product-2.png" alt="" />
                    <div class="align"><a class="wishlist"></a></div>
                  </div>
                  <div class="bord">
                    <div class="space col-xs-12">
                      <div class="col-lg-10 col-sm-10 col-xs-10">
                        <h3>Mug PSD MockUp</h3>
                        <p>by Michael Smith</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <a href="#"><img src="images/img-play.png" alt="" /></a>
                      </div>
                    </div>
                    <div class="bord-small black col-xs-12">
                      <div class="col-lg-3 col-sm-3 border-right col-xs-3">
                        <p>$1.00</p>
                      </div>
                      <div class="col-lg-4 col-sm-4 border-right col-xs-4">
                        <p>2.5Mb</p>
                      </div>
                      <div class="col-lg-3 col-sm-3 border-right col-xs-3">
                        <p>05:12</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <p>
                          <a href="#"><img src="images/img-download.png" alt="" /></a>
                        </p>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-lg-4 col-sm-6 col-xs-12">
                  <div id="third" class="position">
                    <img class="fullwidth" src="images/product-3.png" alt="" />
                    <div class="align"><a class="wishlist"></a></div>
                  </div>
                  <div class="bord">
                    <div class="space col-xs-12">
                      <div class="col-lg-10 col-sm-10 col-xs-10">
                        <h3>Bus Stop Billboard </h3>
                        <p>by Alex Mejia</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <a href="#"><img src="images/img-music.png" alt="" /></a>
                      </div>
                    </div>
                    <div class="bord-small black col-xs-12">
                      <div class="col-lg-3 col-sm-3 border-right col-xs-3">
                        <p>$1.00</p>
                      </div>
                      <div class="col-lg-4 col-sm-4 border-right col-xs-4">
                        <p>1.7Mb</p>
                      </div>
                      <div class="col-lg-3 col-sm-3 border-right col-xs-3">
                        <p>02:11</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <p>
                          <a href="#"><img src="images/img-download.png" alt="" /></a>
                        </p>
                      </div>
                    </div>
                  </div>
                </div><!-- -->
                <div class="col-lg-4 col-sm-6 col-xs-12">
                  <div id="four" class="position">
                    <img class="fullwidth" src="images/product-4.png" alt="" />
                    <div class="align"><a class="wishlist"></a></div>
                  </div>
                  <div class="bord">
                    <div class="space col-xs-12">
                      <div class="col-lg-10 col-sm-10 col-xs-10">
                        <h3>Modern Office </h3>
                        <p>by Jamey Duby</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <a href="#"><img src="images/img-camera.png" alt="" /></a>
                      </div>
                    </div>
                    <div class="bord-small black col-xs-12">
                      <div class="col-lg-4 col-sm-4 border-right col-xs-4">
                        <p>$1.00</p>
                      </div>
                      <div class="col-lg-6 col-sm-6 border-right col-xs-6">
                        <p>524Kb</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <p>
                          <a href="#"><img src="images/img-download.png" alt="" /></a>
                        </p>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-lg-4 col-sm-6 col-xs-12">
                  <div id="five" class="position">
                    <img class="fullwidth" src="images/product-5.png" alt="" />
                    <div class="align"><a class="wishlist"></a></div>
                  </div>
                  <div class="bord">
                    <div class="space col-xs-12">
                      <div class="col-lg-10 col-sm-10 col-xs-10">
                        <h3>Business Card MockUp</h3>
                        <p>by Jamie Bay</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <a href="#"><img src="images/img-play.png" alt="" /></a>
                      </div>
                    </div>
                    <div class="bord-small black col-xs-12">
                      <div class="col-lg-3 col-sm-3 border-right col-xs-3">
                        <p>$1.00</p>
                      </div>
                      <div class="col-lg-4 col-sm-4 border-right col-xs-4">
                        <p>2.5Mb</p>
                      </div>
                      <div class="col-lg-3 col-sm-3 border-right col-xs-3">
                        <p>02:52</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <p>
                          <a href="#"><img src="images/img-download.png" alt="" /></a>
                        </p>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-lg-4 col-sm-6 col-xs-12">
                  <div id="six" class="position">
                    <img class="fullwidth" src="images/product-6.png" alt="" />
                    <div class="align"><a class="wishlist"></a></div>
                  </div>
                  <div class="bord">
                    <div class="space col-xs-12">
                      <div class="col-lg-10 col-sm-10 col-xs-10">
                        <h3>Brick Wall Textures</h3>
                        <p>by Alexandra M.</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <a href="#"><img src="images/img-music.png" alt="" /></a>
                      </div>
                    </div>
                    <div class="bord-small black col-xs-12">
                      <div class="col-lg-3 col-sm-3 border-right col-xs-3">
                        <p>$1.00</p>
                      </div>
                      <div class="col-lg-4 col-sm-4 border-right col-xs-4">
                        <p>1.7Mb</p>
                      </div>
                      <div class="col-lg-3 col-sm-3 border-right col-xs-3">
                        <p>02:11</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <p>
                          <a href="#"><img src="images/img-download.png" alt="" /></a>
                        </p>
                      </div>
                    </div>
                  </div>
                </div><!-- -->
                <div class="col-lg-4 col-sm-6 col-xs-12">
                  <div id="seven" class="position">
                    <img class="fullwidth" src="images/product-7.png" alt="" />
                    <div class="align"><a class="wishlist"></a></div>
                  </div>
                  <div class="bord">
                    <div class="space col-xs-12">
                      <div class="col-lg-10 col-sm-10 col-xs-10">
                        <h3>Christmas Icons</h3>
                        <p>by Jonathan Yorkshire</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <a href="#"><img src="images/img-camera.png" alt="" /></a>
                      </div>
                    </div>
                    <div class="bord-small black col-xs-12">
                      <div class="col-lg-4 col-sm-4 border-right col-xs-4">
                        <p>$1.00</p>
                      </div>
                      <div class="col-lg-6 col-sm-6 border-right col-xs-6">
                        <p>124Kb</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <p>
                          <a href="#"><img src="images/img-download.png" alt="" /></a>
                        </p>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-lg-4 col-sm-6 col-xs-12">
                  <div id="eight" class="position">
                    <img class="fullwidth" src="images/product-8.png" alt="" />
                    <div class="align"><a class="wishlist"></a></div>
                  </div>
                  <div class="bord">
                    <div class="space col-xs-12">
                      <div class="col-lg-10 col-sm-10 col-xs-10">
                        <h3>Business Card MockUp</h3>
                        <p>by Michael Smith</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <a href="#"><img src="images/img-play.png" alt="" /></a>
                      </div>
                    </div>
                    <div class="bord-small black col-xs-12">
                      <div class="col-lg-3 col-sm-3 border-right col-xs-3">
                        <p>$1.00</p>
                      </div>
                      <div class="col-lg-4 col-sm-4 border-right col-xs-4">
                        <p>2.5Mb</p>
                      </div>
                      <div class="col-lg-3 col-sm-3 border-right col-xs-3">
                        <p>05:12</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <p>
                          <a href="#"><img src="images/img-download.png" alt="" /></a>
                        </p>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-lg-4 col-sm-6 col-xs-12">
                  <div id="nine" class="position">
                    <img class="fullwidth" src="images/product-9.png" alt="" />
                    <div class="align"><a class="wishlist"></a></div>
                  </div>
                  <div class="bord">
                    <div class="space col-xs-12">
                      <div class="col-lg-10 col-sm-10 col-xs-10">
                        <h3>Full Color Logo </h3>
                        <p>by Alex Mejia</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <a href="#"><img src="images/img-music.png" alt="" /></a>
                      </div>
                    </div>
                    <div class="bord-small black col-xs-12">
                      <div class="col-lg-3 col-sm-3 border-right col-xs-3">
                        <p>$1.00</p>
                      </div>
                      <div class="col-lg-4 col-sm-4 border-right col-xs-4">
                        <p>1.7Mb</p>
                      </div>
                      <div class="col-lg-3 col-sm-3 border-right col-xs-3">
                        <p>02:11</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <p>
                          <a href="#"><img src="images/img-download.png" alt="" /></a>
                        </p>
                      </div>
                    </div>
                  </div>
                </div><!-- -->
                <div class="col-lg-4 col-sm-6 col-xs-12">
                  <div id="ten" class="position">
                    <img class="fullwidth" src="images/product-10.png" alt="" />
                    <div class="align"><a class="wishlist"></a></div>
                  </div>
                  <div class="bord">
                    <div class="space col-xs-12">
                      <div class="col-lg-10 col-sm-10 col-xs-10">
                        <h3>Savory Food Photo </h3>
                        <p>by Jamey Duby</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <a href="#"><img src="images/img-camera.png" alt="" /></a>
                      </div>
                    </div>
                    <div class="bord-small black col-xs-12">
                      <div class="col-lg-4 col-sm-4 border-right col-xs-4">
                        <p>$1.00</p>
                      </div>
                      <div class="col-lg-6 col-sm-6 border-right col-xs-6">
                        <p>524Kb</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <p>
                          <a href="#"><img src="images/img-download.png" alt="" /></a>
                        </p>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-lg-4 col-sm-6 col-xs-12">
                  <div id="eleven" class="position">
                    <img class="fullwidth" src="images/product-11.png" alt="" />
                    <div class="align"><a class="wishlist"></a></div>
                  </div>
                  <div class="bord">
                    <div class="space col-xs-12">
                      <div class="col-lg-10 col-sm-10 col-xs-10">
                        <h3>Cartboard Tube</h3>
                        <p>by Jamie Bay</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <a href="#"><img src="images/img-play.png" alt="" /></a>
                      </div>
                    </div>
                    <div class="bord-small black col-xs-12">
                      <div class="col-lg-3 col-sm-3 border-right col-xs-3">
                        <p>$1.00</p>
                      </div>
                      <div class="col-lg-4 col-sm-4 border-right col-xs-4">
                        <p>2.5Mb</p>
                      </div>
                      <div class="col-lg-3 col-sm-3 border-right col-xs-3">
                        <p>02:52</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <p>
                          <a href="#"><img src="images/img-download.png" alt="" /></a>
                        </p>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-lg-4 col-sm-6 col-xs-12">
                  <div id="twelve" class="position">
                    <img class="fullwidth" src="images/product-12.png" alt="" />
                    <div class="align"><a class="wishlist"></a></div>
                  </div>
                  <div class="bord">
                    <div class="space col-xs-12">
                      <div class="col-lg-10 col-sm-10 col-xs-10">
                        <h3>Night Sky Photos</h3>
                        <p>by Alexandra M.</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <a href="#"><img src="images/img-music.png" alt="" /></a>
                      </div>
                    </div>
                    <div class="bord-small black col-xs-12">
                      <div class="col-lg-3 col-sm-3 border-right col-xs-3">
                        <p>$1.00</p>
                      </div>
                      <div class="col-lg-4 col-sm-4 border-right col-xs-4">
                        <p>1.7Mb</p>
                      </div>
                      <div class="col-lg-3 col-sm-3 border-right col-xs-3">
                        <p>02:11</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <p>
                          <a href="#"><img src="images/img-download.png" alt="" /></a>
                        </p>
                      </div>
                    </div>
                  </div>
                </div><!-- -->
                <div class="col-lg-4 col-sm-6 col-xs-12">
                  <div id="thirteen" class="position">
                    <img class="fullwidth" src="images/product-13.png" alt="" />
                    <div class="align"><a class="wishlist"></a></div>
                  </div>
                  <div class="bord">
                    <div class="space col-xs-12">
                      <div class="col-lg-10 col-sm-10 col-xs-10">
                        <h3>Business Card Mockup</h3>
                        <p>by Jonathan Yorkshire</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <a href="#"><img src="images/img-camera.png" alt="" /></a>
                      </div>
                    </div>
                    <div class="bord-small black col-xs-12">
                      <div class="col-lg-4 col-sm-4 border-right col-xs-4">
                        <p>$1.00</p>
                      </div>
                      <div class="col-lg-6 col-sm-6 border-right col-xs-6">
                        <p>124Kb</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <p>
                          <a href="#"><img src="images/img-download.png" alt="" /></a>
                        </p>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-lg-4 col-sm-6 col-xs-12">
                  <div id="fourteen" class="position">
                    <img class="fullwidth" src="images/product-14.png" alt="" />
                    <div class="align"><a class="wishlist"></a></div>
                  </div>
                  <div class="bord">
                    <div class="space col-xs-12">
                      <div class="col-lg-10 col-sm-10 col-xs-10">
                        <h3>True Nature Photo</h3>
                        <p>by Michael Smith</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <a href="#"><img src="images/img-play.png" alt="" /></a>
                      </div>
                    </div>
                    <div class="bord-small black col-xs-12">
                      <div class="col-lg-3 col-sm-3 border-right col-xs-3">
                        <p>$1.00</p>
                      </div>
                      <div class="col-lg-4 col-sm-4 border-right col-xs-4">
                        <p>2.5Mb</p>
                      </div>
                      <div class="col-lg-3 col-sm-3 border-right col-xs-3">
                        <p>05:12</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <p>
                          <a href="#"><img src="images/img-download.png" alt="" /></a>
                        </p>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-lg-4 col-sm-6 col-xs-12">
                  <div id="fifteen" class="position">
                    <img class="fullwidth" src="images/product-15.png" alt="" />
                    <div class="align"><a class="wishlist"></a></div>
                  </div>
                  <div class="bord">
                    <div class="space col-xs-12">
                      <div class="col-lg-10 col-sm-10 col-xs-10">
                        <h3>12 Foodies Photos</h3>
                        <p>by Alex Mejia</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <a href="#"><img src="images/img-music.png" alt="" /></a>
                      </div>
                    </div>
                    <div class="bord-small black col-xs-12">
                      <div class="col-lg-3 col-sm-3 border-right col-xs-3">
                        <p>$1.00</p>
                      </div>
                      <div class="col-lg-4 col-sm-4 border-right col-xs-4">
                        <p>1.7Mb</p>
                      </div>
                      <div class="col-lg-3 col-sm-3 border-right col-xs-3">
                        <p>02:11</p>
                      </div>
                      <div class="col-lg-2 col-sm-2 flush text-center col-xs-2">
                        <p>
                          <a href="#"><img src="images/img-download.png" alt="" /></a>
                        </p>
                      </div>
                    </div>
                  </div>
                </div><!-- -->
                <div class="col-xs-12 text-center">
                  <ul class="pagination">
                    <li><a href="#"><img src="images/da-left.png" alt="" /></a></li>
                    <li><a href="#"><img src="images/arrow-left.png" alt="" /></a></li>
                    <li><a href="#">1</a></li>
                    <li><a href="#">2</a></li>
                    <li><a href="#">3</a></li>
                    <li><a href="#">4</a></li>
                    <li>...</li>
                    <li><a href="#">92</a></li>
                    <li><a href="#">93</a></li>
                    <li><a href="#"><img src="images/da-right.png" alt="" /></a></li>
                    <li><a href="#"><img src="images/arrow-right.png" alt="" /></a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section id="footer">
      <div class="container">
        <div class="row">
          <div class="col-lg-3 col-sm-3 small-text-center logo col-xs-12">
            <a href="index.html"><img src="images/logo.png" alt="" /></a>
          </div>
          <div class="col-lg-6 col-sm-6 small-text-center col-xs-12">
            <p>© 2017 Dollar Asset. All rights reserved.</p>
          </div>
          <div class="col-lg-3 col-sm-3 small-text-center text-right text-right col-xs-12">
            <ul>
              <li><a href="#"><img src="images/icon-fb.png" alt="" /></a></li>
              <li><a href="#"><img src="images/icon-ig.png" alt="" /></a></li>
              <li><a href="#"><img src="images/icon-tt.png" alt="" /></a></li>
            </ul>
          </div>
        </div>
      </div>
    </section>
  </section>
</template>

<script>
export default {
  name: 'main',
  data () {
    return {
      msg: 'Welcome to Our Product Selling Application'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
