---
layout: default
title: "Eventos na Azinhaga Digital"
permalink: /eventos/
---

# Eventos na Azinhaga Digital

Informacao sobre eventos

## proximos

<div class="container">
  <section id="countdown">
    <!-- Display the countdown timer in an element -->
    <p class="timer" id="TIMER" style="font-size: 30px"></p>
  </section>
</div>
<script src="/pages/eventos/js/count-down-timer.js"></script>



<div class="container">
  <section id="secretcode">
    <form class="form1" onSubmit="checkCODE(); return false; ">
      <input class="form1" type="text" id="enterCODE" required autofocus />
    </form>
    <p>format "<i>January 1st 2021</i>"</p>

    <p><button id="NEXT" class="button button-green" type="button" style="visibility: hidden" ; onclick="clickNEXT()">NEXT</button></p>
    <p id="checkCODE"></p>
    <p><button class="button button-blue" type="button" value="checkMyCode" onclick="checkCODE()">CHECK MY CODE</button></p>
  </section>
</div>
<script src="/pages/eventos/js/index.js"></script>



---

## passados

```bash
echo "Pass events"
```
