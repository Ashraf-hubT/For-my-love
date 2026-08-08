# For-my-love
A special surprise for Tanis 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For Tanis 🤍</title>

<style>
*{box-sizing:border-box;margin:0;padding:0}

html{scroll-behavior:smooth}

body{
  background:#08080d;
  color:#f5f1ea;
  font-family:Georgia,"Times New Roman",serif;
  overflow-x:hidden;
}

section{
  min-height:100vh;
  display:flex;
  align-items:center;
  justify-content:center;
  text-align:center;
  padding:35px 22px;
  position:relative;
  overflow:hidden;
}

.hero{
  background:
  radial-gradient(circle at 50% 40%,#242035 0%,#0d0c14 40%,#08080d 75%);
}

.content{
  width:100%;
  max-width:720px;
  position:relative;
  z-index:2;
}

.small{
  font-family:Arial,sans-serif;
  font-size:11px;
  letter-spacing:5px;
  text-transform:uppercase;
  opacity:.55;
  margin-bottom:25px;
}

h1{
  font-size:clamp(55px,16vw,110px);
  font-weight:400;
  letter-spacing:2px;
}

.subtitle{
  margin-top:25px;
  font-size:20px;
  line-height:1.8;
  color:#d8d1dc;
}

button{
  margin-top:40px;
  padding:15px 28px;
  border-radius:50px;
  border:1px solid #55505d;
  background:#ffffff08;
  color:white;
  font-size:14px;
  cursor:pointer;
}

button:active{transform:scale(.96)}

.card{
  max-width:680px;
  padding:40px 28px;
  border:1px solid #ffffff15;
  border-radius:25px;
  background:#ffffff05;
  box-shadow:0 20px 80px #0008;
}

.card h2{
  font-size:34px;
  font-weight:400;
}

.card p{
  margin:22px 0;
  font-size:18px;
  line-height:2;
  color:#ddd7df;
}

.divider{
  width:55px;
  height:1px;
  background:#ffffff55;
  margin:30px auto;
}

.memories{
  background:#090910;
}

.quote{
  font-size:clamp(25px,6vw,43px);
  line-height:1.55;
  font-style:italic;
}

.dua{
  background:
  radial-gradient(circle at center,#211a2a,#08080d 70%);
}

.dua h2{
  font-size:clamp(35px,9vw,65px);
  font-weight:400;
  margin-bottom:30px;
}

.dua p{
  font-size:19px;
  line-height:2;
  color:#ddd7df;
}

.arabic{
  font-size:25px!important;
  line-height:2.2!important;
  margin:30px 0!important;
}

.heart{
  font-size:25px;
  margin-bottom:25px;
}

footer{
  padding:25px;
  text-align:center;
  background:#08080d;
  color:#777;
  font-family:Arial,sans-serif;
  font-size:11px;
  letter-spacing:1px;
}

/* soft floating lights */
.light{
  position:absolute;
  width:180px;
  height:180px;
  border-radius:50%;
  background:#bca7ff10;
  filter:blur(45px);
  animation:float 8s infinite ease-in-out;
}

.l1{top:15%;left:10%}
.l2{bottom:15%;right:5%;animation-delay:2s}

@keyframes float{
  50%{transform:translateY(-30px) scale(1.15)}
}

.fade{
  opacity:0;
  transform:translateY(30px);
  transition:1.2s ease;
}

.fade.show{
  opacity:1;
  transform:none;
}
</style>
</head>

<body>

<!-- OPENING -->
<section class="hero">

<div class="light l1"></div>
<div class="light l2"></div>

<div class="content">

<div class="small">A little something</div>

<h1>Tanis</h1>

<p class="subtitle">
Some people become chapters in our lives
that we never stop remembering.
</p>

<button onclick="document.getElementById('letter').scrollIntoView()">
Open this 🤍
</button>

</div>
</section>


<!-- LETTER -->
<section id="letter">

<div class="card fade">

<div class="small">A letter</div>

<h2>Dear Tanis,</h2>

<div class="divider"></div>

<p>
I don't know when you will open this,
or whether you ever will.
I only wanted to leave behind a few words
with no expectation attached to them.
</p>

<p>
We shared a part of life that meant a lot to me.
There were conversations, laughter, memories,
dreams and moments that will always have
their own quiet place in my heart.
</p>

<p>
Life changes.
People change.
And sometimes two people who once
walked together have to continue separately.
</p>

<p>
I've learned that not every beautiful story
has to end the way we once imagined.
</p>

<p>
So there is no request here.
No complaint.
No expectation.
</p>

<p>
<strong>Just a thank you.</strong>
</p>

</div>
</section>


<!-- MEMORY -->
<section class="memories">

<div class="content fade">

<div class="small">What remains</div>

<div class="quote">
“Some memories don't ask to be lived again.
They simply deserve to be remembered
with gratitude.”
</div>

<div class="divider"></div>

<p class="subtitle">
Whatever life brings next,
I hope you always remember that
somewhere in your past,
there was someone who genuinely
wished good things for you.
</p>

</div>
</section>


<!-- FINAL DUA -->
<section class="dua">

<div class="content fade">

<div class="heart">🤍</div>

<h2>
For your new journey,<br>
Tanis
</h2>

<p>
May Allah put peace in your heart,<br>
barakah in your home,<br>
kindness in your days,<br>
and happiness in the life ahead of you.
</p>

<p class="arabic" dir="rtl">
وَجَعَلَ بَيْنَكُم مَّوَدَّةً وَرَحْمَةً
</p>

<p>
May your new chapter be filled with
<strong>mawaddah</strong>,
<strong>rahmah</strong>,
patience and genuine companionship.
</p>

<div class="divider"></div>

<p>
And wherever our roads may lead,<br>
I sincerely hope yours leads to a beautiful place.
</p>

<p style="margin-top:35px;font-size:24px">
Allah Hafiz, Tanis. 🤍
</p>

</div>
</section>


<footer>
Made with respect, gratitude & dua.
</footer>


<script>

const observer = new IntersectionObserver(
(entries)=>{
entries.forEach(entry=>{
if(entry.isIntersecting){
entry.target.classList.add("show");
}
});
},
{threshold:.15}
);

document.querySelectorAll(".fade").forEach(el=>{
observer.observe(el);
});

</script>

</body>
</html>
