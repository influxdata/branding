+++
draft = false
title = "Gradients & How To Use Them"
[menu]
  [menu.main]
    name = "Gradient Usage"
    parent = "colors"
    identifier = "gradients"
    weight = 2
    url = "/colors/gradients/"
+++

<div class="row text-left">
  <div class="col-xs-12">
    <div class="page-header">
      <a class="page-header--anchor" id="title"></a>
      <a href="#title">
        <h1>Gradients & How To Use Them</h1>
      </a>
    </div>
  </div>
  <div class="col-xs-12">
    <hr class="dark" />
    <h5>Usage Rules</h5>
    <ol>
      <li><strong>Gradients are always horizontal, sometimes diagonal but never vertical</strong><br/>(This is a defining part of our style)</li>
      <li>Do not create new gradients</li>
      <li>Do not modify gradients</li>
      <li>High saturation gradients are preferred (Pastel Gothic, Low Difficulty, etc.)</li>
    </ol>
    <hr class="dark" />
  </div>
</div>
<div class="row">
  <div class="col-md-4">
    <h3>Influx Color Wheel</h3>
    <p>This wheel represents the acceptable relationships between colors. For example, <code>I</code> can blend into both <code>C</code> and <code>K</code>, but blending into <code>T</code> would be illegal as it skips a step. One would have to insert <code>C</code> in between to make that a legal gradient.</p>
    <p>Despite being adjacent on the wheel, blending <code>T</code> into <code>K</code> is illegal. This is because they are too far apart in terms of <em>Hue</em> and the result is a muddy gradient. Eventually we will have a 5th product that will fulfill this segment of the wheel, but until this please refrain from this specific gradient.</p><br/><br/>
  </div>
  <div class="col-md-4">
    <img src="/img/color-wheel.svg"/>
    <br/><br/>
  </div>
  <div class="col-md-4">
    <h3>Examples of Illegal Gradients</h3>
    <div class="color-swatch short swatch-grad-illegal-a"></div>
    <code class="color-hex">C3 Star / K3 Rainforest</code>
    <div class="color-swatch short swatch-grad-illegal-b"></div>
    <code class="color-hex">I3 Pool / T3 Curaçao</code>
    <div class="color-swatch short swatch-grad-illegal-c"></div>
    <code class="color-hex">K4 Honeydew / T4 Dreamsicle</code>
  </div>
</div>

<div class="row">
  <div class="col-xs-12">
    <hr class="dark" />
  </div>
</div>

<div class="row">
  <div class="col-md-12">
    <h3>Gradient Orientation</h3>
    <br/><br/>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch swatch-grad-orientation-a">
      <label><span class="icon checkmark"></span> OK</label>
    </div>
    <code class="color-hex">Horizontal</code>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch swatch-grad-orientation-b">
      <label><span class="icon checkmark"></span> OK</label>
    </div>
    <code class="color-hex">Diagonal (45&deg;)</code>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch swatch-grad-orientation-c">
      <label><span class="icon remove"></span> Illegal</label>
    </div>
    <code class="color-hex">Vertical</code>
  </div>
</div>

<div class="row">
  <div class="col-xs-12">
    <hr class="dark" />
  </div>
</div>

<div class="row">
  <div class="col-md-12">
    <h3>Acceptable Mixed Hue Gradients</h3>
    <br/><br/>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch dark swatch-grad-mix-1">
      <label>Beijing Eclipse</label>
    </div>
    <code class="color-hex">T0 Basalt / C0 Shadow</code>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch dark swatch-grad-mix-2">
      <label>Distant Nebula</label>
    </div>
    <code class="color-hex">C0 Shadow / I0 Abyss</code>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch dark swatch-grad-mix-3">
      <label>Spirulina Smoothie</label>
    </div>
    <code class="color-hex">I0 Abyss / K0 Gypsy</code>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch dark swatch-grad-mix-4">
      <label>LA Sunset</label>
    </div>
    <code class="color-hex">T1 Ruby / C1 Void</code>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch dark swatch-grad-mix-5">
      <label>Polar Express</label>
    </div>
    <code class="color-hex">C1 Void / I1 Sapphire</code>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch dark swatch-grad-mix-6">
      <label>Rebel Alliance</label>
    </div>
    <code class="color-hex">I1 Sapphire / K1 Emerald</code>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch dark swatch-grad-mix-7">
      <label>Doc Scott</label>
    </div>
    <code class="color-hex">T2 Fire / C2 Planet</code>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch dark swatch-grad-mix-8">
      <label>Gundam Pilot</label>
    </div>
    <code class="color-hex">C2 Planet / I2 Ocean</code>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch dark swatch-grad-mix-9">
      <label>Tropical Tourist</label>
    </div>
    <code class="color-hex">I2 Ocean / K2 Viridian</code>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch dark swatch-grad-mix-10">
      <label>Desert Festival</label>
    </div>
    <code class="color-hex">T3 Curaçao / C3 Star</code>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch dark swatch-grad-mix-11">
      <label>Miyazaki Sky</label>
    </div>
    <code class="color-hex">C3 Star / I3 Pool</code>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch dark swatch-grad-mix-12">
      <label>Garage Band</label>
    </div>
    <code class="color-hex">I3 Pool / K3 Rainforest</code>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch dark swatch-grad-mix-13">
      <label>Brooklyn Cowboy</label>
    </div>
    <code class="color-hex">T4 Dreamsicle / C4 Comet</code>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch dark swatch-grad-mix-14">
      <label>Pastel Gothic</label>
    </div>
    <code class="color-hex">C4 Comet / I4 Laser</code>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch dark swatch-grad-mix-15">
      <label>Low Difficulty</label>
    </div>
    <code class="color-hex">I4 Laser / K4 Honeydew</code>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch swatch-grad-mix-16">
      <label>Synth Pop</label>
    </div>
    <code class="color-hex">T4 Tungsten / C5 Potassium</code>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch swatch-grad-mix-17">
      <label>Cotton Candy</label>
    </div>
    <code class="color-hex">C5 Potassium / I5 Hydrogen</code>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch swatch-grad-mix-18">
      <label>Hotel Breakfast</label>
    </div>
    <code class="color-hex">I5 Hydrogen / K5 Krypton</code>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch swatch-grad-mix-19">
      <label>Magic Carpet</label>
    </div>
    <code class="color-hex">T6 Marmelade / C6 Moonstone</code>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch swatch-grad-mix-20">
      <label>Cruising Altitude</label>
    </div>
    <code class="color-hex">C6 Moonstone / I6 Neutrino</code>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch swatch-grad-mix-21">
      <label>Coconut Lime</label>
    </div>
    <code class="color-hex">I6 Neutrino / K6 Wasabi</code>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch swatch-grad-mix-22">
      <label>Pastry Cafe</label>
    </div>
    <code class="color-hex">T7 Flan / C7 Creme de Violette</code>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch swatch-grad-mix-23">
      <label>Kawaii Desu</label>
    </div>
    <code class="color-hex">C7 Creme de Violette / I7 Yeti</code>
  </div>
  <div class="col-sm-4">
    <div class="color-swatch swatch-grad-mix-24">
      <label>Robot Logic</label>
    </div>
    <code class="color-hex">I7 Yeti / K7 Mint</code>
  </div>
</div>

<div class="row">
  <div class="col-xs-12">
    <hr class="dark" />
  </div>
</div>