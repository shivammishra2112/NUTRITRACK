<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>NutriTrack – Daily Calorie and Nutrient Tracker</title>
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;700&display=swap" rel="stylesheet">
<style>
:root{--bg:#f4f6fb;--card:#fff;--ink:#1b2440;--mute:#68738f;--line:#e2e7f2;--track:#e9edf6;
--cal:#16a34a;--pro:#2563eb;--carb:#f59e0b;--fat:#ec4899;--fib:#8b5cf6;--over:#dc2626;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#0e1424;--card:#172038;--ink:#e8edfb;--mute:#97a3c4;--line:#27324f;--track:#222c47;--cal:#34d399;--pro:#60a5fa;--carb:#fbbf24;--fat:#f472b6;--fib:#a78bfa;--over:#f87171}}
*{box-sizing:border-box}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
body{margin:0;background:var(--bg);color:var(--ink);font:15px/1.5 "DM Sans",system-ui,-apple-system,"Segoe UI",sans-serif}
.wrap{max-width:820px;margin:0 auto;padding:16px}
.hero{background:linear-gradient(120deg,var(--pro),var(--fib) 45%,var(--fat) 75%,var(--carb));color:#fff;border-radius:18px;padding:16px;margin-bottom:14px;display:flex;justify-content:space-between;align-items:center;gap:10px;flex-wrap:wrap}
.hero h1{margin:0;font-size:22px}.hero p{margin:0;opacity:.9;font-size:13px}
.hero input{width:auto;background:rgba(255,255,255,.22);border-color:rgba(255,255,255,.4);color:#fff;color-scheme:dark}
h2{font-size:17px;margin:0 0 10px}
nav{display:flex;gap:4px;background:var(--track);padding:4px;border-radius:12px;margin-bottom:14px}
nav button{flex:1;border:0;background:none;color:var(--mute);padding:9px 4px;border-radius:9px;font:inherit;font-weight:500;cursor:pointer}
nav button.on{background:var(--card);color:var(--ink);box-shadow:0 1px 4px rgba(0,0,0,.15)}
.card{background:var(--card);border:1px solid var(--line);border-radius:16px;padding:16px;margin-bottom:14px}
label{display:block;font-size:13px;color:var(--mute);margin-bottom:4px}
input,select{width:100%;padding:10px;border:1px solid var(--line);border-radius:9px;background:var(--bg);color:var(--ink);font:inherit}
input:focus,select:focus,button:focus-visible{outline:2px solid var(--fib);outline-offset:1px}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:12px}
.btn{border:0;background:linear-gradient(90deg,var(--pro),var(--fib));color:#fff;padding:11px 16px;border-radius:10px;font:inherit;font-weight:700;cursor:pointer;width:100%}
.stats{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;margin-top:12px;text-align:center}
.stats div{background:var(--bg);border-radius:10px;padding:10px 4px}.stats b{display:block;font-size:18px}.stats span{font-size:12px;color:var(--mute)}
.mute{color:var(--mute);font-size:13px}
.ring{display:flex;align-items:center;gap:18px}.ring svg{flex:0 0 130px;width:130px;height:130px}
.big{font-size:34px;font-weight:700;line-height:1}
.bar{height:10px;background:var(--track);border-radius:6px;overflow:hidden;margin:6px 0}.bar i{display:block;height:100%;border-radius:6px}
.meal-h{display:flex;justify-content:space-between;align-items:center;gap:8px;margin-bottom:6px}
.row{display:flex;justify-content:space-between;align-items:center;gap:8px;padding:8px 0;border-top:1px solid var(--line)}
.row small{display:block;color:var(--mute)}
.row button{border:0;background:none;color:var(--over);cursor:pointer;font-size:18px;padding:0 6px}
.add{display:grid;grid-template-columns:2fr 1fr 1fr;gap:6px;margin-top:10px}
.add .m{grid-column:1/-1;display:grid;grid-template-columns:repeat(4,1fr);gap:6px}
.add .btn{grid-column:1/-1}
.add input{padding:8px}
.m input:nth-child(1){border-color:var(--pro)}.m input:nth-child(2){border-color:var(--carb)}.m input:nth-child(3){border-color:var(--fat)}.m input:nth-child(4){border-color:var(--fib)}
.mgrid{display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-bottom:14px}
.mc{background:var(--card);border:1px solid var(--line);border-top:5px solid var(--c);border-radius:16px;padding:14px}
.mc b{font-size:24px;color:var(--c)}.mc .bar i{background:var(--c)}
.mc .t{font-weight:700}
.split{display:flex;align-items:center;gap:18px;flex-wrap:wrap}
.split svg{width:140px;height:140px}
.dot{display:inline-block;width:10px;height:10px;border-radius:50%;margin-right:6px}
.tabs{display:flex;gap:6px;flex-wrap:wrap}
.tabs button{border:2px solid var(--c);background:none;color:var(--c);padding:5px 12px;border-radius:20px;font:inherit;font-weight:500;cursor:pointer}
.tabs button.on{background:var(--c);color:#fff}
.chart{display:flex;align-items:flex-end;gap:3px;height:160px;border-bottom:1px solid var(--line);overflow-x:auto;margin-top:12px}
.chart div{flex:1;min-width:9px;border-radius:3px 3px 0 0}
.legend{display:flex;justify-content:space-between;font-size:12px;color:var(--mute);margin-top:4px}
.gw{grid-column:1/-1;display:flex;gap:6px;align-items:center;font-size:13px;color:var(--mute)}.gw input{width:80px}
.sv{grid-column:1/-1;display:flex;gap:8px;align-items:center;color:var(--ink);margin:2px 0}.sv input{width:auto}
.fx .fq,.fx .fu{display:none}.edw{border-top:1px solid var(--line);padding-top:8px}.row .eb{color:var(--pro);font-size:16px}
.hide{display:none}
@media(max-width:480px){.ring svg{flex-basis:110px;width:110px;height:110px}.mgrid{grid-template-columns:1fr 1fr}}
</style>
</head>
<body>
<div class="wrap">
<div class="hero"><div><h1>NutriTrack</h1><p>Calories, protein, carbs, fat and fibre in one place</p></div><input type="date" id="date" aria-label="Date"></div>
<nav id="nav"><button data-t="profile">Profile</button><button data-t="log">Food log</button><button data-t="dash">Dashboard</button></nav>

<section id="profile" class="hide"><div class="card">
 <h2>Your health details</h2>
 <p class="mute" style="margin-top:0">Used to work out your daily calorie and nutrient targets. Data stays on this device.</p>
 <div class="grid">
  <div><label>Name</label><input id="p_name"></div>
  <div><label>Age (years)</label><input id="p_age" type="number" min="10" max="100"></div>
  <div><label>Sex</label><select id="p_sex"><option value="m">Male</option><option value="f">Female</option></select></div>
  <div><label>Height (cm)</label><input id="p_h" type="number" min="100" max="230"></div>
  <div><label>Weight (kg)</label><input id="p_w" type="number" min="25" max="300" step="0.1"></div>
  <div><label>Target weight (kg)</label><input id="p_tw" type="number" min="25" max="300" step="0.1"></div>
 </div>
 <div style="margin:12px 0"><label>Activity level</label><select id="p_act">
  <option value="1.2">Sedentary (desk job, little exercise)</option>
  <option value="1.375">Light (exercise 1–3 days/week)</option>
  <option value="1.55">Moderate (exercise 3–5 days/week)</option>
  <option value="1.725">Very active (exercise 6–7 days/week)</option></select></div>
 <div style="margin-bottom:12px"><label>Goal</label><select id="p_goal">
  <option value="-500">Lose weight (about 0.5 kg/week)</option>
  <option value="0">Maintain weight</option>
  <option value="400">Gain weight (about 0.4 kg/week)</option></select></div>
 <div><label>Health conditions or notes (optional)</label><input id="p_note" placeholder="e.g. diabetes, thyroid"></div>
 <div style="margin-top:14px"><button class="btn" id="saveP">Save and calculate</button></div>
 <div id="pres" class="stats hide"></div>
</div></section>

<section id="log" class="hide"><div class="card" id="logTop"></div><div id="meals"></div></section>

<section id="dash" class="hide">
 <div class="card"><h2>Today’s calories</h2><div class="ring" id="todayRing"></div><div id="todayMeals" style="margin-top:12px"></div></div>
 <div class="mgrid" id="macroCards"></div>
 <div class="card"><h2>Where today’s calories came from</h2><div class="split" id="split"></div></div>
 <div class="card">
  <div class="meal-h"><h2 style="margin:0">Monthly view</h2><input type="month" id="month" style="width:auto" aria-label="Month"></div>
  <div class="tabs" id="metricTabs"></div>
  <div class="chart" id="chart"></div><div class="legend"><span>Day 1</span><span id="lastDay"></span></div>
  <div class="stats" id="mStats"></div>
 </div>
</section>
</div>

<script>
const MEALS=[["breakfast","Breakfast"],["lunch","Lunch"],["dinner","Dinner"],["snacks","Evening snacks"]];
const NUT=[["kcal","Calories","kcal","--cal"],["p","Protein","g","--pro"],["c","Carbs","g","--carb"],["f","Fat","g","--fat"],["fb","Fibre","g","--fib"]];
// name, kcal, protein, carbs, fat, fibre (per serving)
const DB=`#Indian
Roti / chapati (1)|100|3|18|2|3
Paratha plain (1)|200|4|28|8|2.5
Aloo paratha (1)|290|6|40|12|3
Naan (1)|260|8|45|5|2
Puri (1)|100|2|12|5|1
Cooked white rice (1 cup)|205|4|45|.4|.6
Jeera rice (1 cup)|230|4|42|5|1
Brown rice (1 cup)|215|5|45|1.8|3.5
Chicken biryani (1 plate)|450|22|55|15|2
Veg biryani (1 plate)|380|9|58|12|4
Khichdi (1 bowl)|210|8|36|4|4
Dal tadka (1 bowl)|150|9|22|3|5
Dal makhani (1 bowl)|250|10|24|13|6
Moong dal (1 bowl)|130|9|20|1.5|5
Rajma (1 bowl)|210|11|33|3|8
Chole / chana masala (1 bowl)|270|12|38|8|10
Sambar (1 bowl)|110|5|17|3|4
Idli (1)|60|2|12|.4|.6
Plain dosa (1)|135|3|22|4|1
Masala dosa (1)|250|5|38|9|3
Uttapam (1)|170|5|28|4|2
Medu vada (1)|130|4|14|7|2
Upma (1 bowl)|200|5|30|7|3
Poha (1 plate)|180|3|34|4|2
Paneer butter masala (1 bowl)|340|14|12|27|2
Palak paneer (1 bowl)|280|15|9|21|3
Paneer tikka (4 pieces)|250|16|6|18|1
Butter chicken (1 bowl)|350|24|10|23|1
Chicken curry (1 bowl)|240|22|6|14|1.5
Tandoori chicken (2 pieces)|260|30|4|13|.5
Chicken tikka (4 pieces)|200|26|3|9|.5
Mutton curry (1 bowl)|320|26|6|22|1.5
Fish curry (1 bowl)|210|22|6|11|1
Egg curry (1 bowl)|230|13|8|16|1.5
Aloo gobi (1 bowl)|150|4|20|7|4
Bhindi masala (1 bowl)|120|3|12|7|4
Mixed vegetable curry (1 bowl)|110|3|14|5|4
Curd / dahi (1 bowl)|100|6|8|5|0
Raita (1 bowl)|80|3|7|4|.5
Curd rice (1 bowl)|220|6|32|7|1
Sweet lassi (1 glass)|220|7|36|5|0
Buttermilk (1 glass)|40|2|5|1|0
Samosa (1)|260|4|28|15|2.5
Pakora (4 pieces)|220|5|20|13|3
Vada pav (1)|290|7|40|11|3
Pav bhaji (1 plate)|400|9|55|16|6
Dhokla (2 pieces)|120|4|18|4|1
Pani puri (6)|200|4|32|6|2
Bhel puri (1 plate)|230|5|38|7|3
Gulab jamun (1)|150|2|22|6|.2
Jalebi (2 pieces)|150|1|28|4|0
Rasgulla (1)|125|3|27|1|0
Kheer (1 bowl)|250|7|38|8|.5
Gajar halwa (1 bowl)|300|5|38|14|2
Masala chai (1 cup)|60|1.5|9|2|0
Filter coffee with milk (1 cup)|70|2|9|3|0
#Chinese
Veg fried rice (1 plate)|330|7|55|9|3
Chicken fried rice (1 plate)|420|18|58|13|2
Egg fried rice (1 plate)|390|12|56|13|2
Schezwan fried rice (1 plate)|400|8|62|13|3
Hakka noodles (1 plate)|380|9|60|11|4
Chicken chow mein (1 plate)|400|18|52|14|3
Veg manchurian dry (1 plate)|260|5|28|14|3
Chicken manchurian (1 plate)|320|20|18|18|2
Chilli chicken (1 plate)|330|26|14|19|2
Chilli paneer (1 plate)|350|16|14|26|2
Veg spring roll (2)|250|5|30|12|2
Veg momos steamed (6)|210|6|36|4|3
Chicken momos steamed (6)|240|14|30|7|2
Dim sum assorted (4)|240|11|28|9|1
Hot and sour soup (1 bowl)|90|5|11|3|1
Sweet corn soup (1 bowl)|100|3|18|2|2
Wonton soup (1 bowl)|180|10|20|6|1
Egg drop soup (1 bowl)|70|5|3|4|0
Kung pao chicken (1 plate)|400|28|16|24|3
Sweet and sour chicken (1 plate)|450|22|50|18|2
Mapo tofu (1 bowl)|280|16|10|20|2
Peking duck with pancakes (3 slices)|300|15|20|17|1
#Asian
Pad thai (1 plate)|540|20|70|20|4
Thai green curry with rice (1 plate)|520|22|60|22|4
Tom yum soup (1 bowl)|90|9|8|3|1
Satay chicken (4 sticks)|280|26|8|16|1
Nasi goreng (1 plate)|480|18|65|16|3
Laksa (1 bowl)|590|23|58|31|3
Pho beef (1 bowl)|450|28|58|10|2
Banh mi (1)|420|20|52|14|3
Fresh spring rolls (2)|140|6|22|3|2
Sushi roll (6 pieces)|250|9|46|3|2
Salmon nigiri (2)|130|9|17|3|.3
Sashimi salmon (5 slices)|180|25|0|8|0
Ramen (1 bowl)|500|20|65|18|3
Udon noodle soup (1 bowl)|380|14|68|5|3
Miso soup (1 bowl)|40|3|5|1|1
Chicken teriyaki (1 plate)|400|32|28|18|1
Tempura (4 pieces)|320|8|28|20|1
Bibimbap (1 bowl)|560|22|82|15|6
Kimchi (1/2 cup)|20|1|4|.3|2
Korean fried chicken (3 pieces)|420|28|20|25|1
Tofu stir fry (1 bowl)|220|14|12|13|3
Edamame (1/2 cup)|95|9|8|4|4
Mochi (1)|100|1|23|.2|.3
#Western
White bread slice (1)|75|2.7|14|1|.8
Brown bread slice (1)|70|3.5|12|1|2
Butter (1 tsp)|36|0|0|4|0
Boiled egg (1)|78|6|.6|5|0
Omelette (2 eggs)|190|13|1|15|0
Scrambled eggs (2 eggs)|200|13|2|15|0
Fried egg (1)|90|6|.4|7|0
Cornflakes with milk (1 bowl)|210|7|40|3|1
Oats porridge (1 bowl)|150|5|27|3|4
Muesli with milk (1 bowl)|280|9|48|6|5
Pancakes with syrup (2)|350|6|60|9|1.5
Waffle (1)|220|6|30|9|1
Toast with peanut butter (1)|190|7|17|11|2.5
Cheese slice (1)|70|4|.5|6|0
Croissant (1)|230|5|26|12|1.5
Margherita pizza (1 slice)|270|11|33|10|2
Pepperoni pizza (1 slice)|300|13|33|13|2
Beef burger (1)|540|28|40|29|2
Chicken burger (1)|480|25|44|22|2
French fries (medium)|365|4|48|17|4
Hot dog (1)|290|10|23|17|1
Club sandwich (1)|520|28|40|26|3
Veg sandwich (1)|250|8|36|8|4
Grilled cheese sandwich (1)|370|14|30|22|1
Spaghetti bolognese (1 plate)|520|26|65|16|5
Pasta alfredo (1 plate)|600|18|68|28|3
Pasta arrabbiata (1 plate)|430|13|75|9|5
Mac and cheese (1 cup)|380|15|43|16|2
Caesar salad (1 bowl)|330|10|12|28|3
Garden salad (1 bowl)|50|2|10|.5|3
Grilled chicken breast (100 g)|165|31|0|3.6|0
Steak, grilled (150 g)|380|40|0|24|0
Fish and chips (1 plate)|600|28|58|30|5
Chicken nuggets (6)|280|14|17|18|1
Mashed potato (1 cup)|210|4|35|7|3
Baked potato (1)|160|4|37|.2|4
Tomato soup (1 bowl)|120|3|20|4|2
Chicken soup (1 bowl)|110|8|10|4|1
Tacos (2)|340|16|34|16|5
Burrito (1)|550|24|68|20|9
#Snacks and sweets
Biscuits (2)|90|1|14|3.5|.4
Potato chips (small pack)|160|2|15|10|1
Popcorn (1 bowl)|110|3|22|1|4
Donut (1)|260|3|31|14|1
Muffin (1)|380|5|52|17|1.5
Brownie (1)|240|3|32|12|1.5
Cookie (1)|150|2|20|7|.8
Chocolate bar (1 small)|230|3|26|13|1.5
Dark chocolate (2 squares)|110|1|9|8|2
Ice cream (1 scoop)|140|2|16|7|.5
Cheesecake (1 slice)|400|7|32|28|.5
Cake (1 slice)|350|4|50|15|1
Almonds (10)|70|2.6|2.5|6|1.5
Cashews (10)|90|2.5|5|7|.5
Walnuts (5 halves)|65|1.5|1.4|6.5|.7
Peanuts (small handful)|160|7|5|14|2.4
Peanut butter (1 tbsp)|95|4|3|8|1
Sprouts salad (1 bowl)|100|8|15|1|5
Boiled chickpeas (1/2 cup)|135|7|22|2|6
#Fruits
Apple (1)|95|.5|25|.3|4.4
Banana (1)|105|1.3|27|.4|3
Orange (1)|62|1.2|15|.2|3
Mango (1 cup)|100|1.4|25|.6|2.6
Grapes (1 cup)|105|1|27|.2|1.4
Papaya (1 cup)|60|.7|15|.4|2.5
Watermelon (1 cup)|46|1|11|.2|.6
Pomegranate (1/2 cup)|72|1.5|16|1|3.5
Guava (1)|37|1.4|8|.5|3
Pineapple (1 cup)|82|1|22|.2|2.3
Strawberries (1 cup)|50|1|12|.5|3
Avocado (1/2)|160|2|9|15|7
#Drinks
Milk, whole (1 glass)|150|8|12|8|0
Milk, toned (1 glass)|120|8|12|5|0
Soy milk (1 glass)|100|7|8|4|1
Black coffee (1 cup)|5|.3|0|0|0
Coffee with milk and sugar (1 cup)|60|2|9|2|0
Tea with milk and sugar (1 cup)|60|1.5|9|2|0
Orange juice (1 glass)|110|2|26|.5|.5
Cola (1 can)|140|0|39|0|0
Coconut water (1 glass)|45|.5|11|.2|2.6
Beer (1 bottle)|150|1.6|13|0|0
Red wine (1 glass)|125|.1|4|0|0
Whey protein shake (1 scoop)|120|24|3|1.5|0
#Protein basics
Paneer (100 g)|265|18|3.5|20|0
Tofu (100 g)|80|8|2|5|1
Chicken breast, cooked (100 g)|165|31|0|3.6|0
Egg white (1)|17|3.6|.2|0|0
Greek yogurt (1 cup)|130|17|9|4|0
Fish, grilled (100 g)|140|24|0|5|0`;
let cust=[];
const allFoods=()=>{const o=[];let cu="";DB.split("\n").forEach(l=>{if(l[0]==="#"){cu=l.slice(1);return}const a=l.split("|");if(a.length>5)o.push([a[0],+a[1],+a[2],+a[3],+a[4],+a[5],cu])});return o.concat(cust.map(x=>[x.name,x.kcal,x.p,x.c,x.f,x.fb,"My foods"]))};
const $=id=>document.getElementById(id);
const r1=n=>Math.round(n*10)/10;
let profile=null,logs={},metric="kcal";
function load(){try{profile=JSON.parse(localStorage.getItem("nt_profile")||"null");logs=JSON.parse(localStorage.getItem("nt_logs")||"{}");cust=JSON.parse(localStorage.getItem("nt_foods")||"[]")}catch(e){profile=null;logs={};cust=[]}}
function save(){try{localStorage.setItem("nt_profile",JSON.stringify(profile));localStorage.setItem("nt_logs",JSON.stringify(logs));localStorage.setItem("nt_foods",JSON.stringify(cust))}catch(e){}}
const iso=d=>d.getFullYear()+"-"+String(d.getMonth()+1).padStart(2,"0")+"-"+String(d.getDate()).padStart(2,"0");
$("date").value=iso(new Date());$("month").value=$("date").value.slice(0,7);
const esc=s=>s.replace(/[&<>"]/g,c=>({"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;"}[c]));

function calc(p){
 const bmr=10*p.w+6.25*p.h-5*p.age+(p.sex==="m"?5:-161),tdee=bmr*p.act;
 const kcal=Math.max(p.sex==="m"?1500:1200,Math.round(tdee+p.goal));
 return{bmr:Math.round(bmr),tdee:Math.round(tdee),bmi:(p.w/Math.pow(p.h/100,2)).toFixed(1),
  t:{kcal,p:Math.round(kcal*.2/4),c:Math.round(kcal*.5/4),f:Math.round(kcal*.3/9),fb:Math.max(25,Math.round(kcal/1000*14))}};
}
const bmiLabel=b=>b<18.5?"Underweight":b<25?"Healthy range":b<30?"Overweight":"Obese";
function showResult(){
 if(!profile)return;const c=calc(profile);$("pres").classList.remove("hide");
 $("pres").innerHTML=`<div><b>${c.bmi}</b><span>BMI · ${bmiLabel(c.bmi)}</span></div><div><b>${c.tdee}</b><span>Maintenance kcal</span></div><div><b>${c.t.kcal}</b><span>Daily target kcal</span></div><div><b style="color:var(--pro)">${c.t.p} g</b><span>Protein</span></div><div><b style="color:var(--carb)">${c.t.c} g</b><span>Carbs</span></div><div><b style="color:var(--fat)">${c.t.f} g</b><span>Fat</span></div><div style="grid-column:2"><b style="color:var(--fib)">${c.t.fb} g</b><span>Fibre</span></div>`;
}
function fillProfile(){
 if(!profile)return;const p=profile;
 $("p_name").value=p.name||"";$("p_age").value=p.age;$("p_sex").value=p.sex;$("p_h").value=p.h;$("p_w").value=p.w;$("p_tw").value=p.tw||"";$("p_act").value=p.act;$("p_goal").value=p.goal;$("p_note").value=p.note||"";showResult();
}
$("saveP").onclick=()=>{
 const p={name:$("p_name").value.trim(),age:+$("p_age").value,sex:$("p_sex").value,h:+$("p_h").value,w:+$("p_w").value,tw:+$("p_tw").value,act:+$("p_act").value,goal:+$("p_goal").value,note:$("p_note").value.trim()};
 if(!p.age||!p.h||!p.w){alert("Enter your age, height and weight to continue.");return}
 profile=p;save();showResult();setTimeout(()=>tab("log"),1200);
};

const dayItems=d=>logs[d]||(logs[d]={breakfast:[],lunch:[],dinner:[],snacks:[]});
function tot(items){const o={kcal:0,p:0,c:0,f:0,fb:0};(items||[]).forEach(x=>NUT.forEach(n=>o[n[0]]+=+x[n[0]]||0));return o}
function dayTot(d){const l=logs[d],o={kcal:0,p:0,c:0,f:0,fb:0};if(l)MEALS.forEach(m=>{const t=tot(l[m[0]]);NUT.forEach(n=>o[n[0]]+=t[n[0]])});return o}

const GW=[[/1\/2 cup/,100],[/yogurt/,245],[/cheesecake/,120],[/cake/,100],[/pizza/,110],[/bread slice/,30],[/cheese slice/,20],[/chapati/,40],[/paratha/,80],[/naan/,90],[/puri \(1\)/,30],[/idli/,40],[/uttapam/,100],[/medu vada/,45],[/vada pav/,120],[/dosa/,90],[/samosa/,60],[/2 eggs/,110],[/^(boiled|fried) egg/,50],[/^egg white/,33],[/banana/,118],[/apple/,180],[/^orange \(1\)/,130],[/guava/,100],[/avocado/,100],[/mango/,165],[/grapes|strawberries/,150],[/pineapple/,165],[/papaya/,145],[/watermelon/,150],[/pomegranate/,90],[/biscuits/,20],[/cookie/,30],[/muffin/,100],[/donut/,60],[/brownie/,60],[/gulab jamun/,40],[/rasgulla/,50],[/jalebi/,60],[/momos|nuggets|spring roll|dim sum|tempura|satay/,100],[/french fries/,120],[/burger/,200],[/hot dog/,100],[/croissant/,60],[/waffle/,75],[/pancakes/,110],[/tacos/,150],[/burrito/,250],[/sushi roll/,150],[/nigiri/,60],[/sashimi/,100],[/chocolate bar/,45],[/dark chocolate/,20],[/ice cream/,66],[/almonds/,12],[/cashews/,15],[/walnuts/,10],[/peanuts/,30],[/peanut butter/,16],[/popcorn/,20],[/chips \(/,30],[/mochi/,40],[/tsp/,5],[/tbsp/,16],[/pakora|dhokla/,80],[/pani puri/,100],[/pav bhaji/,300],[/tikka|tandoori/,120],[/glass/,240],[/can\)|bottle/,330],[/scoop/,30],[/cup\)/,200],[/bowl/,200],[/plate/,300]];
function gram(n){const c=cust.find(x=>x.name===n);if(c&&c.w)return c.w;const m=n.match(/\((\d+) g\)/);if(m)return +m[1];for(const [re,g] of GW)if(re.test(n.toLowerCase()))return g;return 100}
let ed=null;
const frm=(md,k,i,btns)=>`<div class="add ${md==="food"?"fx":""}" data-mode="${md}" data-k="${k}" data-i="${i}"><input list="foods" placeholder="Search foods or type a new one" class="fn" style="grid-column:1/-1"><input type="number" min="0.25" step="0.25" value="1" class="fq" aria-label="Quantity"><select class="fu" aria-label="Unit"><option value="s">servings</option><option value="g">grams</option></select><input type="number" min="0" placeholder="kcal" class="fk" aria-label="Calories"><div class="gw hide">1 serving ≈ <input type="number" min="1" class="fw" value="100" aria-label="Grams per serving"> g. Change the grams or quantity and the nutrients update.</div><div class="m"><input type="number" min="0" step="0.1" placeholder="Protein g" class="fp"><input type="number" min="0" step="0.1" placeholder="Carbs g" class="fc"><input type="number" min="0" step="0.1" placeholder="Fat g" class="ff"><input type="number" min="0" step="0.1" placeholder="Fibre g" class="fb"></div>${btns}</div>`;
const SAVE_BTNS='<button class="btn ok">Save changes</button><button class="btn can" style="background:var(--mute)">Cancel</button>';
function wire(a,init,onSave){
 const q=s=>a.querySelector(s),fn=q(".fn"),fx=a.classList.contains("fx"),F=[[".fk","kcal"],[".fp","p"],[".fc","c"],[".ff","f"],[".fb","fb"]];
 let base=Object.assign({},init.b||{});
 const mult=()=>{if(fx)return 1;const n=+q(".fq").value||0;return q(".fu").value==="g"?n/(+q(".fw").value||100):n};
 const show=()=>{const m=mult();F.forEach(([s,k])=>{q(s).value=base[k]==null?"":(k==="kcal"?Math.round(base[k]*m):r1(base[k]*m))})};
 const gw=()=>q(".gw").classList.toggle("hide",!fx&&q(".fu").value!=="g");
 fn.value=init.name||"";q(".fu").value=init.u||"s";q(".fq").value=init.qty||1;q(".fw").value=init.w||100;
 if(q(".fu").value==="g"){q(".fq").step=1;q(".fq").min=1}
 gw();show();
 F.forEach(([s,k])=>q(s).oninput=()=>{base[k]=(+q(s).value||0)/(mult()||1)});
 q(".fq").oninput=show;q(".fw").oninput=show;
 q(".fu").onchange=()=>{const g=q(".fu").value==="g";q(".fq").value=g?(q(".fw").value||100):1;q(".fq").step=g?1:.25;q(".fq").min=g?1:.25;gw();show()};
 fn.oninput=()=>{const f=allFoods().find(x=>x[0]===fn.value);if(f){base={kcal:f[1],p:f[2],c:f[3],f:f[4],fb:f[5]};q(".fw").value=gram(f[0]);if(q(".fu").value==="g")q(".fq").value=q(".fw").value;show()}};
 q(".ok").onclick=()=>{
  const name=fn.value.trim();if(!name||q(".fk").value===""){alert("Enter a food and its calories.");return}
  const m=mult()||1,v=z=>+q(z).value||0,sv=q(".svc");
  onSave({name,qty:+q(".fq").value||1,u:q(".fu").value,w:+q(".fw").value||100,t:{kcal:v(".fk"),p:v(".fp"),c:v(".fc"),f:v(".ff"),fb:v(".fb")},b:{kcal:v(".fk")/m,p:v(".fp")/m,c:v(".fc")/m,f:v(".ff")/m,fb:v(".fb")/m}},sv&&sv.checked);
 };
 const cn=q(".can");if(cn)cn.onclick=()=>{ed=null;renderLog()};
}
const entry=r=>({name:r.name,qty:r.qty,u:r.u,w:r.w,b:r.b,kcal:Math.round(r.t.kcal),p:r1(r.t.p),c:r1(r.t.c),f:r1(r.t.f),fb:r1(r.t.fb)});
function myFoodsHtml(){return `<div class="card"><h2>My foods</h2>${cust.length?cust.map((x,i)=>ed&&ed.m==="food"&&ed.i===i?`<div class="edw">${frm("food",0,i,SAVE_BTNS)}</div>`:`<div class="row"><span>${esc(x.name)}<small>${x.kcal} kcal · P ${x.p}g · C ${x.c}g · F ${x.f}g · Fibre ${x.fb}g per serving${x.w?" (≈ "+x.w+" g)":""}</small></span><span><button class="eb" data-m="food" data-i="${i}" aria-label="Edit food">✎</button><button class="dc" data-i="${i}" aria-label="Delete food">×</button></span></div>`).join(""):'<div class="mute">Can’t find a food? Type its name and values in any meal above, tick “Save as a new food”, and it will appear in search from then on.</div>'}</div>`}
function renderLog(){
 const d=$("date").value,l=dayItems(d),t=dayTot(d),tg=calc(profile).t;
 $("logTop").innerHTML=`<div class="meal-h"><h2 style="margin:0">${new Date(d+"T00:00").toLocaleDateString(undefined,{weekday:"long",day:"numeric",month:"short"})}</h2><b>${Math.round(t.kcal)} / ${tg.kcal} kcal</b></div><div class="bar"><i style="width:${Math.min(100,t.kcal/tg.kcal*100)}%;background:${t.kcal>tg.kcal?"var(--over)":"var(--cal)"}"></i></div><div class="mute">${t.kcal>tg.kcal?Math.round(t.kcal-tg.kcal)+" kcal over your target":Math.round(tg.kcal-t.kcal)+" kcal left today"}</div>`;
 $("meals").innerHTML=MEALS.map(([k,n])=>{const s=tot(l[k]);return `<div class="card" style="border-left:5px solid var(--${{breakfast:"carb",lunch:"cal",dinner:"pro",snacks:"fat"}[k]})"><div class="meal-h"><h2 style="margin:0">${n}</h2><b>${Math.round(s.kcal)} kcal</b></div>
 ${l[k].length?l[k].map((x,i)=>ed&&ed.m==="log"&&ed.k===k&&ed.i===i?`<div class="edw">${frm("log",k,i,SAVE_BTNS)}</div>`:`<div class="row"><span>${esc(x.name)}${x.u==="g"?" · "+x.qty+" g":x.qty>1?" × "+x.qty:""}<small>P ${r1(x.p||0)}g · C ${r1(x.c||0)}g · F ${r1(x.f||0)}g · Fibre ${r1(x.fb||0)}g</small></span><span>${Math.round(x.kcal)} kcal <button class="eb" data-m="log" data-k="${k}" data-i="${i}" aria-label="Edit">✎</button><button class="xb" data-k="${k}" data-i="${i}" aria-label="Remove">×</button></span></div>`).join(""):'<div class="mute">Nothing added yet.</div>'}
 ${frm("add",k,0,'<label class="sv"><input type="checkbox" class="svc"> Save as a new food in My foods</label><button class="btn ok">Add to '+n.toLowerCase()+'</button>')}</div>`}).join("")+myFoodsHtml()+`<datalist id="foods">${allFoods().map(f=>`<option value="${esc(f[0])}" label="${f[6]}">`).join("")}</datalist>`;
 document.querySelectorAll(".xb").forEach(b=>b.onclick=()=>{ed=null;dayItems(d)[b.dataset.k].splice(+b.dataset.i,1);save();renderLog()});
 document.querySelectorAll(".dc").forEach(b=>b.onclick=()=>{ed=null;cust.splice(+b.dataset.i,1);save();renderLog()});
 document.querySelectorAll(".eb").forEach(b=>b.onclick=()=>{ed={m:b.dataset.m,k:b.dataset.k,i:+b.dataset.i};renderLog()});
 document.querySelectorAll(".add").forEach(a=>{
  const md=a.dataset.mode,k=a.dataset.k,i=+a.dataset.i;let init={};
  if(md==="log"){const x=dayItems(d)[k][i],w=x.w||gram(x.name),mm=(x.u==="g"?x.qty/w:x.qty)||1;init={name:x.name,u:x.u||"s",qty:x.qty,w,b:x.b||{kcal:x.kcal/mm,p:(x.p||0)/mm,c:(x.c||0)/mm,f:(x.f||0)/mm,fb:(x.fb||0)/mm}}}
  if(md==="food"){const x=cust[i];init={name:x.name,u:"s",qty:1,w:x.w||gram(x.name),b:{kcal:x.kcal,p:x.p,c:x.c,f:x.f,fb:x.fb}}}
  wire(a,init,(r,sv)=>{
   if(md==="add"){dayItems(d)[k].push(entry(r));if(sv&&!allFoods().some(x=>x[0].toLowerCase()===r.name.toLowerCase()))cust.push({name:r.name,w:r.u==="g"?r.w:0,kcal:r1(r.b.kcal),p:r1(r.b.p),c:r1(r.b.c),f:r1(r.b.f),fb:r1(r.b.fb)})}
   else if(md==="log"){dayItems(d)[k][i]=entry(r);ed=null}
   else{cust[i]={name:r.name,w:r.w,kcal:r1(r.t.kcal),p:r1(r.t.p),c:r1(r.t.c),f:r1(r.t.f),fb:r1(r.t.fb)};ed=null}
   save();renderLog();
  });
 });
}
function ring(t,tg){
 const r=54,c=2*Math.PI*r,p=Math.min(1,t/tg);
 return `<svg viewBox="0 0 130 130" role="img" aria-label="${Math.round(t)} of ${tg} kcal"><circle cx="65" cy="65" r="${r}" fill="none" stroke="var(--track)" stroke-width="12"/><circle cx="65" cy="65" r="${r}" fill="none" stroke="${t>tg?"var(--over)":"var(--cal)"}" stroke-width="12" stroke-linecap="round" stroke-dasharray="${c*p} ${c}" transform="rotate(-90 65 65)"/><text x="65" y="70" text-anchor="middle" font-size="22" font-weight="700" fill="var(--ink)">${Math.round(p*100)}%</text></svg>`;
}
function donut(parts){
 const total=parts.reduce((a,x)=>a+x.v,0),r=50,c=2*Math.PI*r;let off=0;
 if(!total)return `<svg viewBox="0 0 130 130"><circle cx="65" cy="65" r="${r}" fill="none" stroke="var(--track)" stroke-width="22"/></svg>`;
 return `<svg viewBox="0 0 130 130" role="img" aria-label="Calorie split">`+parts.map(x=>{const len=x.v/total*c,s=`<circle cx="65" cy="65" r="${r}" fill="none" stroke="var(${x.col})" stroke-width="22" stroke-dasharray="${len} ${c-len}" stroke-dashoffset="${-off}" transform="rotate(-90 65 65)"/>`;off+=len;return s}).join("")+`</svg>`;
}
function renderDash(){
 const tg=calc(profile).t,today=iso(new Date()),t=dayTot(today),l=logs[today]||{};
 $("todayRing").innerHTML=ring(t.kcal,tg.kcal)+`<div><div class="big">${Math.round(t.kcal)}</div><div class="mute">of ${tg.kcal} kcal eaten today</div><div style="margin-top:6px;font-weight:500">${t.kcal>tg.kcal?Math.round(t.kcal-tg.kcal)+" kcal over":Math.round(tg.kcal-t.kcal)+" kcal remaining"}</div></div>`;
 const mcol={breakfast:"--carb",lunch:"--cal",dinner:"--pro",snacks:"--fat"};
 $("todayMeals").innerHTML=MEALS.map(([k,n])=>{const v=tot(l[k]).kcal;return `<div style="margin-bottom:8px"><div class="meal-h" style="margin:0"><span>${n}</span><span>${Math.round(v)} kcal</span></div><div class="bar"><i style="width:${t.kcal?v/t.kcal*100:0}%;background:var(${mcol[k]})"></i></div></div>`}).join("");
 $("macroCards").innerHTML=NUT.slice(1).map(([k,n,u,col])=>{const pc=Math.min(100,t[k]/tg[k]*100);return `<div class="mc" style="--c:var(${col})"><div class="t">${n}</div><b>${r1(t[k])}</b> <span class="mute">/ ${tg[k]} ${u}</span><div class="bar"><i style="width:${pc}%"></i></div><div class="mute">${Math.round(pc)}% of daily goal</div></div>`}).join("");
 const parts=[{n:"Protein",v:t.p*4,col:"--pro"},{n:"Carbs",v:t.c*4,col:"--carb"},{n:"Fat",v:t.f*9,col:"--fat"}],pt=parts.reduce((a,x)=>a+x.v,0);
 $("split").innerHTML=donut(parts)+`<div>${parts.map(x=>`<div><span class="dot" style="background:var(${x.col})"></span>${x.n}: <b>${pt?Math.round(x.v/pt*100):0}%</b> <span class="mute">(${Math.round(x.v)} kcal)</span></div>`).join("")}<div class="mute" style="margin-top:6px">Aim for roughly 20% protein, 50% carbs and 30% fat.</div></div>`;
 $("metricTabs").innerHTML=NUT.map(([k,n,u,col])=>`<button data-k="${k}" style="--c:var(${col})" class="${k===metric?"on":""}">${n}</button>`).join("");
 document.querySelectorAll("#metricTabs button").forEach(b=>b.onclick=()=>{metric=b.dataset.k;renderDash()});
 const [y,m]=$("month").value.split("-").map(Number),days=new Date(y,m,0).getDate(),vals=[];
 for(let i=1;i<=days;i++)vals.push(dayTot(`${y}-${String(m).padStart(2,"0")}-${String(i).padStart(2,"0")}`)[metric]);
 const N=NUT.find(x=>x[0]===metric),goal=tg[metric],mx=Math.max(goal*1.2,...vals);
 $("chart").innerHTML=vals.map((v,i)=>`<div style="height:${Math.max(2,v/mx*100)}%;background:var(${v>goal&&metric==="kcal"?"--over":N[3]});opacity:${v?1:.2}" title="Day ${i+1}: ${r1(v)} ${N[2]}"></div>`).join("");
 $("lastDay").textContent="Day "+days;
 const lg=vals.filter(v=>v>0),sm=lg.reduce((a,b)=>a+b,0),avg=lg.length?sm/lg.length:0,hit=lg.filter(v=>metric==="kcal"?v<=goal:v>=goal).length;
 $("mStats").innerHTML=`<div><b style="color:var(${N[3]})">${r1(avg)}</b><span>Avg ${N[2]} / day</span></div><div><b>${Math.round(sm).toLocaleString()}</b><span>Month total (${N[2]})</span></div><div><b>${hit}/${lg.length}</b><span>Days ${metric==="kcal"?"within":"meeting"} goal</span></div>`;
}

function tab(t){ed=null;
 if(t!=="profile"&&!profile)t="profile";
 ["profile","log","dash"].forEach(s=>$(s).classList.toggle("hide",s!==t));
 document.querySelectorAll("#nav button").forEach(b=>b.classList.toggle("on",b.dataset.t===t));
 if(t==="log")renderLog();if(t==="dash")renderDash();
 try{history.replaceState(null,"","#"+t)}catch(e){}
}
document.querySelectorAll("#nav button").forEach(b=>b.onclick=()=>tab(b.dataset.t));
$("date").onchange=()=>{ed=null;if(!$("log").classList.contains("hide"))renderLog()};
$("month").onchange=renderDash;
load();fillProfile();
const h=location.hash.slice(1);tab(profile?(["log","dash","profile"].includes(h)?h:"log"):"profile");
</script>
</body>
</html>
