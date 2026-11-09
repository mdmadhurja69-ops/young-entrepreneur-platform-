<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#102a43">
<title>Young Entrepreneur Platform</title>
<style>
:root{--navy:#102a43;--blue:#2563eb;--mint:#d9fbe9;--ink:#172b4d;--muted:#62748a;--bg:#f4f7fb;--line:#e3eaf2;--white:#fff;--orange:#f59e0b}
*{box-sizing:border-box}html{scroll-behavior:smooth}body{margin:0;font-family:system-ui,-apple-system,"Noto Sans Bengali",sans-serif;background:var(--bg);color:var(--ink)}button,input,select,textarea{font:inherit}button{cursor:pointer}.topbar{background:var(--navy);color:#fff;padding:13px max(18px,calc((100% - 1160px)/2));display:flex;align-items:center;justify-content:space-between;gap:16px;position:sticky;top:0;z-index:5}.brand{font-weight:850;letter-spacing:-.5px;font-size:19px;display:flex;align-items:center;gap:9px}.logo{width:34px;height:34px;border-radius:11px;background:linear-gradient(135deg,#6ee7b7,#60a5fa);display:grid;place-items:center;color:#102a43;font-weight:900}.nav{display:flex;gap:7px;flex-wrap:wrap}.nav button{border:0;background:transparent;color:#d9e6f2;padding:9px 12px;border-radius:9px}.nav button.active,.nav button:hover{background:#24445f;color:#fff}.auth{background:#fff;color:var(--navy);border:0;border-radius:10px;padding:9px 14px;font-weight:750}.wrap{max-width:1160px;margin:auto;padding:26px 18px 60px}.hero{background:linear-gradient(120deg,#102a43,#1e4970 65%,#2563eb);border-radius:24px;padding:36px;color:#fff;display:grid;grid-template-columns:1.5fr 1fr;gap:20px;align-items:center;overflow:hidden}.eyebrow{color:#9ef0c5;font-weight:750;font-size:13px;letter-spacing:.5px}.hero h1{font-size:clamp(29px,5vw,48px);line-height:1.13;margin:12px 0}.hero p{color:#d9e7f4;max-width:620px;line-height:1.75}.hero-actions{display:flex;gap:10px;flex-wrap:wrap;margin-top:22px}.primary,.secondary{border:0;border-radius:11px;padding:12px 17px;font-weight:800}.primary{background:#a7f3d0;color:#123047}.secondary{background:#ffffff1c;color:#fff;border:1px solid #ffffff55}.hero-art{min-height:180px;display:grid;place-items:center}.orbit{width:190px;height:190px;border:1px solid #ffffff55;border-radius:50%;display:grid;place-items:center;position:relative;background:#ffffff0c}.orbit:before,.orbit:after{content:"";position:absolute;border:1px dashed #ffffff66;border-radius:50%;inset:20px}.orbit:after{inset:45px}.orbit span{font-size:65px;z-index:1}.stats{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin:18px 0 28px}.stat,.panel,.card{background:var(--white);border:1px solid var(--line);border-radius:16px}.stat{padding:16px 18px}.stat b{font-size:22px;display:block}.stat small{color:var(--muted)}.section-head{display:flex;justify-content:space-between;align-items:end;gap:12px;margin:30px 0 14px}.section-head h2{margin:0;font-size:23px}.section-head p{margin:4px 0 0;color:var(--muted);font-size:14px}.filters{display:flex;gap:9px;flex-wrap:wrap;margin-bottom:15px}.field{border:1px solid var(--line);border-radius:10px;padding:10px 12px;background:#fff;color:var(--ink);min-width:0}.search{flex:1;min-width:180px}.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:14px}.card{overflow:hidden}.thumb{height:130px;display:grid;place-items:center;font-size:48px;background:linear-gradient(135deg,#e0f2fe,#dcfce7)}.card-body{padding:15px}.tag{display:inline-block;background:#eff6ff;color:#1d4ed8;padding:4px 8px;border-radius:99px;font-size:11px;font-weight:750}.card h3{margin:9px 0 5px;font-size:17px}.card p{color:var(--muted);font-size:13px;line-height:1.6;margin:0 0 12px}.price{font-weight:850;font-size:18px}.card-foot{display:flex;align-items:center;justify-content:space-between;gap:8px;margin-top:12px}.small-btn{border:0;background:var(--navy);color:#fff;border-radius:9px;padding:8px 11px;font-size:12px;font-weight:750}.outline-btn{border:1px solid var(--line);background:white;color:var(--ink);border-radius:9px;padding:8px 11px;font-size:12px;font-weight:750}.feature-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:14px}.feature{padding:18px}.feature .emoji{font-size:28px}.feature h3{margin:8px 0 5px}.feature p{color:var(--muted);font-size:13px;line-height:1.65;margin:0}.notice{background:#fff8e7;border:1px solid #f6dfaa;border-radius:14px;padding:14px 16px;color:#704b0a;font-size:13px;line-height:1.7;margin-top:24px}.panel{padding:20px}.form-grid{display:grid;grid-template-columns:1fr 1fr;gap:12px}.form-grid label{font-size:13px;font-weight:700;display:grid;gap:6px}.form-grid .full{grid-column:1/-1}.form-grid textarea{min-height:80px;resize:vertical}.empty{text-align:center;padding:28px;color:var(--muted);grid-column:1/-1}.hidden{display:none!important}.footer{border-top:1px solid var(--line);margin-top:40px;padding-top:20px;color:var(--muted);font-size:12px;line-height:1.7}.modal{position:fixed;inset:0;background:#071827aa;display:none;place-items:center;padding:18px;z-index:10}.modal.show{display:grid}.modal-box{background:white;border-radius:18px;padding:22px;max-width:440px;width:100%;max-height:90vh;overflow:auto}.modal-box h2{margin-top:0}.modal-box p{color:var(--muted);font-size:13px;line-height:1.6}.modal-actions{display:flex;gap:8px;flex-wrap:wrap;margin-top:16px}.close{float:right;border:0;background:#eef2f7;border-radius:8px;padding:5px 9px}.toast{position:fixed;bottom:18px;left:50%;transform:translateX(-50%);background:#102a43;color:white;padding:11px 16px;border-radius:10px;display:none;z-index:20;font-size:13px;max-width:90%;text-align:center}.toast.show{display:block}
@media(max-width:800px){.hero{grid-template-columns:1fr;padding:26px}.hero-art{display:none}.grid,.feature-grid{grid-template-columns:repeat(2,1fr)}.nav{display:none}.topbar{flex-wrap:wrap}.stats{gap:8px}.stat{padding:12px}.stat b{font-size:18px}}
@media(max-width:520px){.grid,.feature-grid{grid-template-columns:1fr}.stats{grid-template-columns:1fr 1fr}.stats .stat:last-child{grid-column:1/-1}.form-grid{grid-template-columns:1fr}.form-grid .full{grid-column:auto}.section-head{align-items:start;flex-direction:column}.brand{font-size:16px}}
</style>
</head>
<body>
<header class="topbar">
 <div class="brand"><span class="logo">Y</span> Young Entrepreneur Platform</div>
 <nav class="nav" aria-label="প্রধান মেনু">
  <button class="active" data-go="home">হোম</button><button data-go="market">মার্কেটপ্লেস</button><button data-go="learn">শিখুন</button><button data-go="sell">বিক্রি করুন</button>
 </nav>
 <button class="auth" id="loginBtn">লগইন / অ্যাকাউন্ট</button>
</header>
<main class="wrap" id="home">
 <section class="hero">
  <div><div class="eyebrow">IDEAS • LEARNING • OPPORTUNITY</div>
   <h1>তোমার আইডিয়া,<br>তোমার উদ্যোগ।</h1>
   <p>শেখো, নিজের তৈরি জিনিস দেখাও, নিরাপদভাবে কেনাবেচার সুযোগ খুঁজে নাও—তরুণ উদ্যোক্তাদের জন্য এক জায়গা।</p>
   <div class="hero-actions"><button class="primary" data-scroll="market">মার্কেটপ্লেস দেখো ↗</button><button class="secondary" data-scroll="sell">বিজ্ঞাপন যোগ করো</button></div>
  </div>
  <div class="hero-art"><div class="orbit"><span>🚀</span></div></div>
 </section>
 <section class="stats">
  <div class="stat"><b id="listingCount">০</b><small>ডেমো ও তোমার বিজ্ঞাপন</small></div>
  <div class="stat"><b>৩টি</b><small>শেখার বিভাগ</small></div>
  <div class="stat"><b>ফ্রি</b><small>প্রোটোটাইপ ব্যবহার</small></div>
 </section>
 <section id="market">
  <div class="section-head"><div><h2>🛍️ কমিউনিটি মার্কেটপ্লেস</h2><p>বই, হস্তশিল্প, স্টেশনারি ও অন্যান্য উপযোগী জিনিস খুঁজে দেখো।</p></div></div>
  <div class="filters"><input class="field search" id="searchInput" placeholder="কী খুঁজছ? যেমন: বই, কলম..." aria-label="পণ্য খুঁজুন"><select class="field" id="categoryFilter"><option value="সব">সব বিভাগ</option><option>বই</option><option>স্টেশনারি</option><option>হস্তশিল্প</option><option>অন্যান্য</option></select></div>
  <div class="grid" id="listingGrid"></div>
 </section>
 <section id="learn">
  <div class="section-head"><div><h2>📚 অনলাইন শেখার কর্নার</h2><p>বৈধ ও উন্মুক্ত শিক্ষাসামগ্রী এবং শেখার অভিজ্ঞতা।</p></div></div>
  <div class="feature-grid">
   <article class="card feature"><div class="emoji">📖</div><h3>বিনামূল্যে বই পড়া</h3><p>পাবলিক-ডোমেইন ও উন্মুক্ত লাইসেন্সের বই পড়ার সংগ্রহ তৈরি করার জায়গা।</p><a href="https://www.gutenberg.org/" target="_blank" rel="noopener" class="small-btn" style="display:inline-block;text-decoration:none;margin-top:12px">Project Gutenberg ↗</a></article>
   <article class="card feature"><div class="emoji">🎓</div><h3>ফ্রি কোর্স</h3><p>বিভিন্ন বিষয়ের উন্মুক্ত পাঠ ও শেখার উপকরণ খুঁজে দেখো।</p><a href="https://www.khanacademy.org/" target="_blank" rel="noopener" class="small-btn" style="display:inline-block;text-decoration:none;margin-top:12px">Khan Academy ↗</a></article>
   <article class="card feature"><div class="emoji">🧪</div><h3>ফ্রি ট্রায়াল / ডেমো</h3><p>সফটওয়্যার বা অনলাইন টুলের বৈধ ফ্রি ডেমো ও ট্রায়াল সম্পর্কে জানো। শর্ত ও বয়সসীমা দেখে নিও।</p><a href="https://www.canva.com/" target="_blank" rel="noopener" class="small-btn" style="display:inline-block;text-decoration:none;margin-top:12px">Canva ↗</a></article>
  </div>
 </section>
 <section id="sell">
  <div class="section-head"><div><h2>➕ নতুন বিজ্ঞাপন যোগ করো</h2><p>তোমার পণ্য বা সেবার তথ্য দাও। এটি এখন শুধু এই ব্রাউজারেই সংরক্ষিত হবে।</p></div></div>
  <div class="panel">
   <form id="listingForm" class="form-grid">
    <label>পণ্যের নাম<input class="field" name="title" required maxlength="55" placeholder="যেমন: নবম শ্রেণির গণিত বই"></label>
    <label>বিভাগ<select class="field" name="category"><option>বই</option><option>স্টেশনারি</option><option>হস্তশিল্প</option><option>অন্যান্য</option></select></label>
    <label>দাম (টাকা)<input class="field" name="price" type="number" min="0" max="100000" required placeholder="যেমন: ১৫০"></label>
    <label>ইমোজি<input class="field" name="emoji" maxlength="4" value="📦" placeholder="📚"></label>
    <label class="full">সংক্ষিপ্ত বিবরণ<textarea class="field" name="description" required maxlength="220" placeholder="পণ্যের অবস্থা, বৈশিষ্ট্য ইত্যাদি লিখো"></textarea></label>
    <div class="full"><button class="primary" type="submit">বিজ্ঞাপন যোগ করো</button></div>
   </form>
  </div>
 </section>
 <div class="notice"><b>🔒 শিক্ষার্থীদের নিরাপত্তা আগে:</b> এটি একটি ডেমো প্রোটোটাইপ। এখানে বাস্তব কেনাবেচা, পেমেন্ট বা পরিচয় যাচাই চালু নেই। অপ্রাপ্তবয়স্ক ব্যবহারকারীদের ক্ষেত্রে অভিভাবকের অনুমতি ও তত্ত্বাবধান জরুরি। ফোন নম্বর, বাসার ঠিকানা, পাসওয়ার্ড বা স্কুলের ব্যক্তিগত তথ্য প্রকাশ কোরো না। সন্দেহজনক বিজ্ঞাপন বা অপরিচিত ব্যক্তির সঙ্গে একা দেখা কোরো না।</div>
 <footer class="footer">© 2026 Young Entrepreneur Platform · শেখা ও উদ্যোগের একটি শিক্ষামূলক প্রোটোটাইপ।<br>বই/কোর্সের লিংক সংশ্লিষ্ট সেবাদাতার নিজস্ব সাইটে যায়; তাদের নিয়ম ও লাইসেন্স মেনে ব্যবহার করো।</footer>
</main>
<div class="modal" id="loginModal" role="dialog" aria-modal="true" aria-labelledby="loginTitle">
 <div class="modal-box"><button class="close" id="closeModal">✕</button><h2 id="loginTitle">স্বাগতম!</h2><p>Google বা স্কুল অ্যাকাউন্ট দিয়ে সাইন-ইন এখানে এখনো সক্রিয় নয়। এই বাটনগুলো শুধু ভবিষ্যৎ ফিচারের নমুনা—কোনো তথ্য নেওয়া বা পাঠানো হয় না।</p><div class="modal-actions"><button class="primary" id="googleDemo">Google দিয়ে চালিয়ে যাও</button><button class="outline-btn" id="schoolDemo">স্কুল আইডি দিয়ে চালিয়ে যাও</button></div><p><b>নিরাপত্তা:</b> স্কুল আইডি বা Google পাসওয়ার্ড এই ডেমোতে লিখবে না। বাস্তব লগইনের জন্য নিরাপদ OAuth ব্যবস্থা ও সার্ভার সেটআপ করতে হবে।</p></div>
</div>
<div class="toast" id="toast" role="status"></div>
<script>
const demoListings=[
 {id:1,title:"নবম শ্রেণির গণিত সহায়িকা",category:"বই",price:180,emoji:"📘",description:"ভালো অবস্থার সহায়িকা বই। নমুনা বিজ্ঞাপন—বাস্তব বিক্রেতা নয়।"},
 {id:2,title:"হাতে তৈরি বুকমার্ক",category:"হস্তশিল্প",price:40,emoji:"🎨",description:"রঙিন কাগজে তৈরি বুকমার্কের ডেমো বিজ্ঞাপন।"},
 {id:3,title:"জ্যামিতি বক্স",category:"স্টেশনারি",price:120,emoji:"📐",description:"শিক্ষার্থীদের জন্য স্টেশনারি পণ্যের উদাহরণ।"}
];
let userListings=[];try{userListings=JSON.parse(localStorage.getItem("yepListings")||"[]")}catch(e){}
const all=()=>[...userListings,...demoListings];
const bn=n=>new Intl.NumberFormat("bn-BD").format(n);
function render(){const q=document.getElementById("searchInput").value.trim().toLowerCase();const c=document.getElementById("categoryFilter").value;const items=all().filter(x=>(c==="সব"||x.category===c)&&(x.title.toLowerCase().includes(q)||x.description.toLowerCase().includes(q)));document.getElementById("listingCount").textContent=bn(all().length);const grid=document.getElementById("listingGrid");grid.innerHTML="";if(!items.length){grid.innerHTML='<div class="empty">কোনো বিজ্ঞাপন পাওয়া যায়নি। অন্য শব্দ দিয়ে খুঁজে দেখো।</div>';return}items.forEach(x=>{const el=document.createElement("article");el.className="card";const thumb=document.createElement("div");thumb.className="thumb";thumb.textContent=x.emoji||"📦";const body=document.createElement("div");body.className="card-body";const tag=document.createElement("span");tag.className="tag";tag.textContent=x.category;const h=document.createElement("h3");h.textContent=x.title;const p=document.createElement("p");p.textContent=x.description;const foot=document.createElement("div");foot.className="card-foot";const price=document.createElement("span");price.className="price";price.textContent="৳"+bn(x.price);const btn=document.createElement("button");btn.className="outline-btn";btn.textContent="বিস্তারিত";btn.onclick=()=>toast("এটি ডেমো বিজ্ঞাপন। বাস্তব যোগাযোগ ও লেনদেন এখনো চালু নয়।");foot.append(price,btn);body.append(tag,h,p,foot);el.append(thumb,body);grid.append(el)})}
function toast(msg){const t=document.getElementById("toast");t.textContent=msg;t.classList.add("show");setTimeout(()=>t.classList.remove("show"),2800)}
document.getElementById("searchInput").addEventListener("input",render);document.getElementById("categoryFilter").addEventListener("change",render);
document.getElementById("listingForm").addEventListener("submit",e=>{e.preventDefault();const f=new FormData(e.target);const item={id:Date.now(),title:String(f.get("title")).trim(),category:f.get("category"),price:Number(f.get("price")),emoji:String(f.get("emoji")||"📦"),description:String(f.get("description")).trim()};userListings.unshift(item);try{localStorage.setItem("yepListings",JSON.stringify(userListings))}catch(err){}e.target.reset();render();toast("বিজ্ঞাপনটি এই ডিভাইসে যোগ হয়েছে।");document.getElementById("market").scrollIntoView()});
const modal=document.getElementById("loginModal");document.getElementById("loginBtn").onclick=()=>modal.classList.add("show");document.getElementById("closeModal").onclick=()=>modal.classList.remove("show");modal.addEventListener("click",e=>{if(e.target===modal)modal.classList.remove("show")});document.getElementById("googleDemo").onclick=()=>toast("Google লগইন এখনো সংযুক্ত করা হয়নি।");document.getElementById("schoolDemo").onclick=()=>toast("স্কুল আইডি যাচাই এখনো সংযুক্ত করা হয়নি।");
document.querySelectorAll("[data-scroll]").forEach(b=>b.onclick=()=>document.getElementById(b.dataset.scroll).scrollIntoView({behavior:"smooth"}));document.querySelectorAll("[data-go]").forEach(b=>b.onclick=()=>{document.querySelectorAll("[data-go]").forEach(x=>x.classList.remove("active"));b.classList.add("active");document.getElementById(b.dataset.go).scrollIntoView({behavior:"smooth"})});
render();
</script>
</body>
</html>
