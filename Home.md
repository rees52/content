

----

`<h1 style="background-color: #dde4f0; color: #000000; padding: 12px;"><span style="color: #000000;"><strong>SPECIFICATIONS</strong></span></h1>
<p></p>
<ol>
<li><strong><span><span>  </span></span></strong><strong><span>Li-Po Battery</span></strong></li>
</ol>
<p><span> </span></p>
<ul>
<li><span><span>         </span></span><span>Material: Li-polymer </span></li>
<li><span><span>         </span></span><span>Voltage: 11.1V </span></li>
<li><span><span>         </span></span><span>Capacity: 3000mAh </span></li>
<li><span><span>         </span></span><span>Cell: 3S </span></li>
<li><span><span>         </span></span><span>Discharge: 30C </span></li>
<li><span><span>         </span></span><span>Charge Plug: JST-XH </span></li>
<li><span><span>         </span></span><span>Discharge Plug: Dean-style T connector</span></li>
</ul>
<p>                        </p>
<ol start="2">
<li><strong><span><span>  </span></span></strong><strong><span>Brushless motor 1400 KV </span></strong></li>
</ol>
<p><strong><span>         </span></strong></p>
<ul>
<li><span><span>         </span></span><span>Rpm/V: 1400kv</span></li>
<li><span><span>         </span></span><span>Shaft: 3.17mm</span></li>
<li><span><span>         </span></span><span>Voltage: 2S~3S (7.4v to 11.1v)</span></li>
<li><span><span>         </span></span><span>Weight: 50g</span></li>
<li><span><span>         </span></span><span>Watts: 205w</span></li>
<li><span><span>         </span></span><span>Max Current: 21A</span></li>
<li><span><span>         </span></span><span>ESC: 40A</span></li>
<li><span><span>         </span></span><span>Suggested Prop: 7x4(3S) ~ 9x4.7 (2S) </span></li>
<li><span><span>         </span></span><span>Mounting Hole Bolt Circle: 16mm or 19mm</span></li>
</ul>
<p><strong><span> </span></strong></p>
<p><br /><br /></p>
<h1 style="background-color: #dde4f0; color: #000000; padding: 12px;"><span style="color: #000000;"><strong>HARDWARE REQUIRED</strong></span></h1>
<p></p>
<ul>
<li>         Arduino uno with USB Cable – 1</li>
<li>         ESC(Electronic Speed control) 30 A – 1</li>
<li>         Potentiometer 10k – 1</li>
<li>         LIPO Battery – 1</li>
<li>         Brushless Motor 1400 kv – 1</li>
<li>         Single stand wire – 1</li>
<li>         Jumper wire (male to male ) – 3</li>
</ul>
<h1 style="background-color: #dde4f0; color: #000000; padding: 12px;"><span style="color: #000000;"><strong>SOFTWARE REQUIRED</strong></span></h1>
<p></p>
<p></p>
<p><span>Arduino IDE 1.8.4 (programmable platform for Arduino )</span></p>
<p><span>You can download form here (</span><span><span><a href="https://www.arduino.cc/en/Main/Software">https://www.arduino.cc/en/Main/Software</a>)</span></span></p>
<p><span><span><img src="http://devs.rees52.com/img/cms/SOFT.PNG" alt="" width="684" height="260" /></span></span></p>
<p></p>
<h1 style="background-color: #dde4f0; color: #000000; padding: 12px;"><span style="color: #000000;"><strong>PIN DESCRIPTION</strong></span></h1>
<p></p>
<p></p>
<ul>
<li><strong style="color: #4a4a4a; font-size: 11px;">Potentiometer</strong></li>
</ul>
<p></p>
<p><strong><img src="http://devs.rees52.com/img/cms/POTENTIOMETER.jpg" alt="" width="285" height="285" /></strong></p>
<p></p>
<p></p>
<ul>
<li><strong style="color: #4a4a4a;">ESC (Electronic speed controller)</strong></li>
</ul>
<p><br /><br /></p>
<p><img src="http://devs.rees52.com/img/cms/rs042l/2_1.png" alt="" width="741" height="399" /></p>
<p></p>
<p></p>
<h1 style="background-color: #dde4f0; color: #000000; padding: 12px;"><span style="color: #000000;"><strong>CIRCUIT DIAGRAM</strong></span></h1>
<p></p>
<p><img src="http://devs.rees52.com/img/cms/rs042l/1.jpg" alt="" width="954" height="668" /><br /><br /></p>
<p></p>
<ol>
<li><span><span>      </span></span><span>First connect the three terminals of Brushless motor to the three terminals of the ESC.</span></li>
<li><span><span>      </span></span><span>Connect the signal wire of ESC mostly white or yellow colour to any PWM pin 8 of Arduino uno</span></li>
<li><span><span>      </span></span><span>You can use more than one pins for controlling many motors.</span></li>
<li><span><span>      </span></span><span>Connect the Potentiometer to the Vcc or 5v pin of the Arduino and the Ground.</span></li>
<li><span><span>      </span></span><span>Connect the third terminal that is the variable pin to the Analog pin A0 You can power the Arduino using the BEC (Battery Eliminator Circuit) Present in your ESC. To use the BEC just connect the red thick wire to the Vin Pin of Arduino .It can provide 5V.Not all ESC’s have a BEC, in this case you can use a external 5v power supply. After Powering the Arduino now connect the Lipo battery to your ESC.</span></li>
</ol>
<h1 style="background-color: #dde4f0; color: #000000; padding: 12px;"><span style="color: #000000;"><strong>CODE</strong></span></h1>
<p><br />
https://github.com/rees52/content/blob/master/code_RS042L
[Click to download the code](https://pastebin.com/embed_iframe/PjVqDDRJ)
<p><br /><br /></p>
<h1 style="background-color: #dde4f0; color: #000000; padding: 12px;"><span style="color: #000000;"><strong>OUTPUT</strong></span></h1>
<p><span>Connect all the Circuit . </span><span>The speed is controlled with the ESC (Electronic Speed Control), which controls the speed based on the entry voltage.</span><span> </span></p>`




