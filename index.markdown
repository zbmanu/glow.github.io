---
layout: default
title: Glow in the Dark Wall Clock (Lidl Livarno)
---

<article class="project">
  <header class="project-header">
    <h1>{{ page.title }}</h1>
    
    <div class="project-meta">
      <div class="byline">
        By <a href="https://github.com/sbnbob">sbnbob</a> 
        in <a href="/circuits">Circuits</a> » 
        <a href="/circuits/clocks">Clocks</a>
      </div>
      
    </div>
    
    <div class="actions">
      <button class="btn">Save PDF</button>
      <button class="btn">Add to Collection</button>
      <button class="btn">Favorite</button>
      <button class="btn">More Options</button>
    </div>
  </header>
  
  <main class="project-content">
    <div class="gallery">
      <img src="https://content.instructables.com/F9E/FEDU/M0KJRDFZ/F9EFEDUM0KJRDFZ.jpg?width=270&auto=webp" 
           alt="Glow in the Dark Wall Clock">
      <img src="httpscontent.instructables.com/FBS/1373/M0KJR6BI/FBS1373M0KJR6BI.jpg?width=270&auto=webp" 
           alt="Glow in the Dark Wall Clock">
      <img src="https://content.instructables.com/F72/UA5U/M0KJR7GR/F72UA5UM0KJR7GR.jpg?width=270&auto=webp" 
           alt="Glow in the Dark Wall Clock">
    </div>
    
    <div class="project-steps">
      <section class="step">
        <h2>Introduction</h2>
        <div class="step-content">
          <p>To be able to see my wall clock's time hands at night I bought some luminescent paint from Aliexpress - the traditional copper-doped zinc sulfide kind, not the strontium aluminate type. It's just bright enough to tell the time if you have good night vision.</p>
          <p>The hands are difficult to paint without removing them, and removing the hands is quite difficult - and risks damaging the clock in the process. Clockmakers like to use a clock hand puller tool (which relies on the center pin, a part that isn't very strong in this clock), DIY pry bars, (top) cutting pliers, scissors, etc.</p>
          <p>Keep in mind that the paint will add weight to the hands, causing the stepper motors to work harder and drain the battery faster.</p>
          <p>After prying off the rim and removing the glass plate, I tried to pull off the second hand. However, I had to use so much force that I was afraid it might snap, so I decided to brush the paint on without removing the hands.</p>
        </div>
      </section>
      
      <section class="step">
        <h2>Supplies</h2>
        <div class="step-content">
          <ol>
            <li>Fluorescent Paint (I chose one of the three white/translucent colored bottles listed as color 01).</li>
            <li>Mobile Phone (Curved) Spudger</li>
            <li>Heat-Gun</li>
            <li>Vise</li>
          </ol>
        </div>
      </section>
      
      <section class="step">
        <h2>Step 1: Remove All Hands</h2>
        <div class="step-content">
          <ol>
            <li>Press and hold reset for 4 seconds (or remove the battery and put it back in). The hands move to the 12:00:00-o‘clock position and stop.</li>
            <li>Remove the battery with all hands still pointing to the 12:00:00-o‘clock position.</li>
            <li>With a spudger move around the base of the clock until the aluminum rim comes loose and can be removed.</li>
            <li>Pull off the second hand.</li>
            <li>Pull off the hour hand if possible together with its holder.</li>
            <li>Pull off the minute hand.</li>
          </ol>
        </div>
      </section>
      
      <section class="step">
        <h2>Step 2: Paint Hour and Minute Hands</h2>
        <div class="step-content">
          <ol>
            <li>If the paint is like pudding, stir in a small amount of water.</li>
            <li>Spread it out over the hands. I put on thick watery dome-like layers held in place by surface tension.</li>
            <li>Dry with a heat gun.</li>
            <li>Apply next layer.</li>
            <li>Test with UV light until satisfactory result.</li>
          </ol>
          <p>Apply the same amount of paint and layers to both hands so they both glow equally bright.</p>
        </div>
      </section>
      
      <section class="step">
        <h2>Step 3: Reassemble</h2>
        <div class="step-content">
          <ol>
            <li>With the clock mechanism still at the 12:00:00-o‘clock position push the hour hand back onto its shaft (lightly if you want to test the result first).</li>
            <li>If necessary press fit the minute hand back onto its brass holder. Then push both back onto the minute shaft.</li>
            <li>Press the second hand back onto its pin.</li>
            <li>Put the glass and the rim back in place.</li>
          </ol>
          <p>You may want to lightly fit the hour and minute hands first to test if the result is to your liking or whether more paint is required to improve visibility. I can read the clock clearly at night from three meters away without using UV or any extra light to charge the hands.</p>
        </div>
      </section>
      
      <section class="step">
        <h2>Step 4: Gearbox Teardown</h2>
        <div class="step-content">
          <p>Some pictures to show the internals and how to reassemble them. Several cogs have an embossed number on them. The movement has two glob top circuits (chip-on-board), a ferrite coil antenna, two Lavet-type stepping motors, two crystals, a side-viewing IR-emitter (designated JS-JS on the board), paired with its receiving photo diode (D1) to track clock hand position. Some cogs are see-through and solid, while others are black and have a unique pattern of cutouts and holes allowing identification and tracking (optical rotary encoders).</p>
          <p>Note: I placed the antenna with its coil right above a crystal oscillator, although it may have been on the other side originally.</p>
        </div>
      </section>
    </div>
  </main>
</article>

<style>
  .project {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
  }
  
  .project-header {
    margin-bottom: 2rem;
  }
  
  .project-content {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
    font-size: 16px;
    line-height: 1.6;
  }
  
  .project-content h2 {
    margin: 2rem 0 1rem;
    color: #333;
    font-size: 1.8rem;
  }
  
  .project-content .step {
    margin-bottom: 3rem;
  }
  
  .project-content .step-content {
    margin: 1rem 0;
  }
  
  .project-content .step-content p {
    margin-bottom: 1rem;
  }
  
  .project-content .step-content ol li {
    margin-bottom: 0.5rem;
  }
  
  .gallery {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin: 20px 0;
  }
  
  .gallery img {
    flex: 1;
    max-width: 300px;
    height: auto;
  }
  
  .btn {
    display: inline-block;
    padding: 8px 16px;
    background: #f0f0f0;
    border: 1px solid #ddd;
    border-radius: 4px;
    cursor: pointer;
    font-size: 0.9rem;
  }
  
  .btn:hover {
    background: #e0e0e0;
  }
  
  .stats {
    display: flex;
    gap: 20px;
    margin: 10px 0;
    color: #666;
    font-size: 0.9rem;
  }
  
  .byline {
    display: flex;
    align-items: center;
    gap: 8px;
    margin: 10px 0;
  }
  
  .byline a {
    color: #0070d0;
    text-decoration: none;
    font-weight: 600;
  }
  
  .byline a:hover {
    text-decoration: underline;
  }
  
  .actions {
    display: flex;
    gap: 15px;
    margin: 20px 0;
    flex-wrap: wrap;
  }
  
  .step-content {
    margin: 1rem 0;
  }
  
  .step-content p {
    margin-bottom: 1rem;
  }
  
  .step-content ol, .step-content ul {
    margin-bottom: 1.5rem;
  }
  
  .step-content li {
    margin-bottom: 0.5rem;
  }
  
  @media (max-width: 768px) {
    .project {
      padding: 10px;
    }
    
    .gallery {
      grid-template-columns: 1fr;
    }
  }
</style>

