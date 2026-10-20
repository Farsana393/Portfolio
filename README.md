[Portfolio.html](https://github.com/user-attachments/files/33720313/Portfolio.html)
# Portfolio<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Farsana Fathima NA | Data Analyst</title>
<meta name="description" content="Data Analyst in Muscat, Oman. Power BI, Tableau, SQL, Advanced Excel and Python dashboards.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@600;800&family=IBM+Plex+Sans:wght@400;500&family=IBM+Plex+Mono:wght@400&display=swap" rel="stylesheet">
<style>
:root{
  color-scheme:light;
  --bg:#ffffff; --alt:#f5f8fb; --card:#ffffff; --ink:#14213d; --muted:#55627a;
  --line:#dde3ec; --accent:#0f766e; --warm:#f2a900;
  --code-bg:#14213d; --code-ink:#dbe6ff;
  --head:"Bricolage Grotesque","Segoe UI",Arial,sans-serif;
  --body:"IBM Plex Sans","Segoe UI",Arial,sans-serif;
  --mono:"IBM Plex Mono",Consolas,monospace;
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{margin:0;background:var(--bg);color:var(--ink);font:400 1.05rem/1.65 var(--body)}
a{color:inherit}
:focus-visible{outline:3px solid var(--warm);outline-offset:3px}
.wrap{max-width:1040px;margin:0 auto;padding:0 20px}
section{padding:64px 0}
section.alt{background:var(--alt)}
h1,h2,h3{font-family:var(--head);line-height:1.1;margin:0}
h2{font-size:clamp(1.8rem,4vw,2.5rem);margin-bottom:8px}
.sub{color:var(--muted);max-width:60ch;margin:0 0 32px}

nav{position:sticky;top:0;z-index:5;background:rgba(255,255,255,.92);backdrop-filter:blur(8px);border-bottom:1px solid var(--line)}
nav .wrap{display:flex;justify-content:space-between;align-items:center;height:58px}
nav b{font-family:var(--head);font-size:1.3rem;font-weight:800}
nav ul{display:flex;gap:18px;list-style:none;margin:0;padding:0}
nav a{text-decoration:none;color:var(--muted);font-size:.95rem}
nav a:hover{color:var(--ink)}

.hero{padding-top:56px}
.hero .wrap{max-width:820px}
.me{display:flex;align-items:center;gap:20px;margin-bottom:22px}
.avatar{width:166px;height:166px;border-radius:50%;object-fit:cover;border:4px solid #fff;box-shadow:0 0 0 3px var(--accent),0 10px 24px rgba(20,33,61,.18);flex:none}
.hero h1{font-size:45px;font-weight:800;line-height:1.1}
.role{font:800 22px/1.1 var(--head);color:var(--accent);margin-top:6px}
.loc{font:500 .95rem var(--mono);color:var(--muted);margin-top:8px}
.hero p{color:var(--muted);max-width:48ch;margin:18px 0 26px}
.btns{display:flex;gap:12px;flex-wrap:wrap}
.btn{display:inline-block;padding:12px 22px;border-radius:8px;font-weight:500;text-decoration:none;border:2px solid var(--accent);transition:transform .15s}
.btn.main{background:var(--accent);color:#fff}
.btn:hover{transform:translateY(-2px)}

.skills{display:grid;grid-template-columns:repeat(auto-fit,minmax(190px,1fr));gap:16px}
.skill{background:var(--card);border:1px solid var(--line);border-radius:10px;padding:18px}
.skill h3{font-size:1.2rem;margin-bottom:6px}
.skill p{margin:0;color:var(--muted);font-size:.92rem}
.s1{border-top:4px solid #0f766e}.s2{border-top:4px solid #1d7a46}.s3{border-top:4px solid var(--warm)}.s4{border-top:4px solid #3b6fd4}.s5{border-top:4px solid #6b7bb5}

.filters{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:24px}
.chip{font:inherit;font-size:.9rem;padding:7px 16px;border-radius:99px;border:1px solid var(--line);background:#fff;color:var(--ink);cursor:pointer;transition:background .2s,color .2s}
.chip[aria-pressed="true"]{background:var(--ink);color:#fff;border-color:var(--ink)}
.grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(310px,1fr));gap:22px;align-items:start}
.card{background:var(--card);border:1px solid var(--line);border-radius:14px;overflow:hidden;transition:transform .25s,box-shadow .25s}
.card:hover{transform:translateY(-6px);box-shadow:0 14px 30px rgba(20,33,61,.12)}
.card.hide{display:none}
.thumb{display:block;width:100%;height:190px;padding:0;border:0;border-bottom:1px solid var(--line);position:relative;cursor:zoom-in;overflow:hidden;background:var(--alt)}
.thumb img{width:100%;height:100%;object-fit:cover;object-position:top left;transition:transform .5s}
.card:hover .thumb img{transform:scale(1.06)}
.thumb .badge{position:absolute;right:10px;bottom:10px;background:rgba(20,33,61,.85);color:#fff;font:.78rem var(--mono);padding:3px 10px;border-radius:99px}
.thumb.stat{cursor:default;display:flex;flex-direction:column;justify-content:center;align-items:flex-start;padding:22px;background:linear-gradient(135deg,var(--c1),var(--c2));color:#fff}
.thumb.stat b{font:800 2.6rem/1 var(--head)}
.thumb.stat span{margin-top:8px;opacity:.9;font-size:.95rem}
.cbody{padding:18px 20px 20px}
.cbody h3{font-size:1.3rem;margin-bottom:6px}
.cbody p{margin:0 0 12px;color:var(--muted);font-size:.95rem}
.tags{display:flex;gap:6px;flex-wrap:wrap;margin-bottom:12px}
.tag{font:.78rem var(--mono);padding:2px 9px;border-radius:6px;background:rgba(15,118,110,.1);color:var(--accent)}
.more{display:grid;grid-template-rows:0fr;transition:grid-template-rows .35s}
.more>div{overflow:hidden}
.card.open .more{grid-template-rows:1fr}
.more dl{margin:0 0 12px;font-size:.93rem}
.more dt{font-weight:500;margin-top:8px}
.more dd{margin:0;color:var(--muted)}
.more ul{margin:2px 0 0;padding-left:18px;color:var(--muted)}
.dl{display:inline-block;margin-top:12px;padding:8px 14px;border:1.5px solid var(--accent);border-radius:8px;color:var(--accent);font-size:.92rem;font-weight:500;text-decoration:none;transition:background .2s,color .2s}
.dl:hover{background:var(--accent);color:#fff}
.fileRow{display:block}
.toggle{font:inherit;background:none;border:0;padding:0;color:var(--accent);font-weight:500;cursor:pointer}

dialog{border:0;border-radius:12px;padding:0;max-width:min(1100px,94vw);width:100%;background:#fff;box-shadow:0 20px 60px rgba(0,0,0,.35)}
dialog::backdrop{background:rgba(10,18,36,.72)}
.lb-top{display:flex;justify-content:space-between;align-items:center;padding:12px 16px;border-bottom:1px solid var(--line)}
.lb-top b{font-family:var(--head)}
.lb-img{max-height:74vh;overflow:auto;background:var(--alt)}
.lb-img img{display:block;width:100%;height:auto}
.lb-nav{display:flex;justify-content:space-between;align-items:center;padding:10px 16px;gap:10px}
.lb-nav button,.lb-top button{font:inherit;border:1px solid var(--line);background:#fff;border-radius:8px;padding:6px 14px;cursor:pointer}
.lb-nav span{color:var(--muted);font-size:.92rem;text-align:center}

.exp{list-style:none;margin:0;padding:0;border-left:2px solid var(--line)}
.exp li{padding:0 0 26px 22px;position:relative}
.exp li::before{content:"";position:absolute;left:-7px;top:7px;width:12px;height:12px;border-radius:50%;background:var(--accent)}
.exp h3{font-size:1.2rem}
.exp small{color:var(--muted);font-family:var(--mono);font-size:.82rem}
.exp ul{margin:8px 0 0;padding-left:18px;color:var(--muted);font-size:.95rem}

.about{display:grid;grid-template-columns:1.3fr 1fr;gap:36px}
.facts{list-style:none;margin:0;padding:20px;background:var(--card);border:1px solid var(--line);border-radius:12px}
.facts li{padding:8px 0;border-bottom:1px solid var(--line);font-size:.97rem}
.facts li:last-child{border:0}
.contact{text-align:center}
.contact .sub{margin-inline:auto}
footer{text-align:center;color:var(--muted);font-size:.9rem;padding:28px 0;border-top:1px solid var(--line)}

@media (max-width:760px){
  .avatar{width:112px;height:112px}
  .hero h1{font-size:24px}
  .role{font-size:19px}
  nav b{font-size:1.05rem}
  .about{grid-template-columns:1fr}
  nav ul{gap:11px}nav a{font-size:.85rem}
  section{padding:48px 0}
}
@media (prefers-reduced-motion:reduce){
  *{transition:none!important;animation:none!important}
  html{scroll-behavior:auto}
}
</style>
</head>
<body>

<nav><div class="wrap">
  <b>Farsana Fathima NA</b>
  <ul>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#experience">Experience</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</div></nav>

<header class="hero"><div class="wrap">
  <div>
    <div class="me">
      <img class="avatar" src="images/profile.jpg" alt="Portrait of Farsana Fathima NA">
      <div>
        <h1>Farsana Fathima NA</h1>
        <div class="role">Data Analyst</div>
        <div class="loc">Muscat, Oman</div>
      </div>
    </div>
    <p>I turn raw data into decision-ready dashboards. I build interactive reports in Power BI, Tableau and Excel, clean data with Power Query and SQL, and write DAX measures that stakeholders can trust across sales, finance, HR and project performance.</p>
    <div class="btns">
      <a class="btn main" href="#projects">See my projects</a>
      <a class="btn" href="Farsana Fathima NA - Data Analyst.pdf" target="_blank" rel="noopener">Download resume</a>
    </div>
  </div>
</div></header>

<section id="projects" class="alt"><div class="wrap">
  <h2>Projects</h2>
  
  <div class="filters" id="filters"></div>
  <div class="grid" id="grid"></div>
</div></section>

<section id="experience"><div class="wrap">
  <h2>Experience</h2>
  <p class="sub">Hands-on training in business reporting and analytics.</p>
  <ul class="exp">
    <li>
      <h3>Trainee, Rows and Columns</h3><small>Feb 2026 – Jun 2026</small>
      <ul>
        <li>Completed advanced training in Microsoft Excel and Power Query for business and financial data analysis.</li>
        <li>Cleaned, validated and transformed multi-source datasets with Power Query to make reporting more reliable.</li>
        <li>Produced executive-style reports with charts, trend analysis and variance analysis.</li>
        <li>Worked on real business and finance case studies under deadlines.</li>
      </ul>
    </li>
    <li>
      <h3>Trainee, Data Analytics &amp; Power BI, Voleergo Solutions</h3><small>May 2025 – Jun 2025</small>
      <ul>
        <li>Designed Power BI dashboards that track business KPIs for cross-functional stakeholders.</li>
        <li>Wrote and optimised SQL queries for data extraction, transformation and analysis.</li>
        <li>Built data models with calculated columns and DAX measures to streamline recurring reports.</li>
      </ul>
    </li>
  </ul>
</div></section>

<section id="skills" class="alt"><div class="wrap">
  <h2>Skills</h2>
  <p class="sub">The tools I use to clean, model and present data.</p>
  <div class="skills">
    <div class="skill s3"><h3>Power BI</h3><p>Dashboards, data models, DAX measures, slicers, KPI reporting.</p></div>
    <div class="skill s5"><h3>Tableau</h3><p>Interactive dashboards, funnels and department analysis.</p></div>
    <div class="skill s2"><h3>Excel</h3><p>Advanced Excel, Power Query, trend and variance analysis.</p></div>
    <div class="skill s1"><h3>SQL</h3><p>Queries for data extraction, transformation and analysis.</p></div>
    <div class="skill s4"><h3>Python</h3><p>Programming for data work, using Visual Studio Code.</p></div>
  </div>
</div></section>

<section id="about"><div class="wrap about">
  <div>
    <h2>About me</h2>
    <p>I'm a data analyst with a Master of Technology in Computer Science and Engineering. I like turning large, messy datasets into clear visuals that help people make decisions.</p>
    <p>My work covers sales, payroll, HR, finance and project performance.</p>
    <p>My process is simple: clean and transform the data in Power Query, model it with DAX measures, and present KPIs, trends and variances so stakeholders can decide quickly. I care most about reports that are accurate, easy to read and end in a clear recommendation.</p>
    <p>I gained this experience through two traineeships. At Rows and Columns (Feb to Jun 2026), I cleaned and validated multi-source datasets and produced executive-style reports on real business and finance cases. At Voleergo Solutions (May to Jun 2025), I built interactive Power BI dashboards, wrote SQL queries for extraction and analysis, and created DAX measures that streamlined recurring reporting.</p>
    <p>I'm now looking for a data analyst role where I can keep turning data into clear decisions.</p>
  </div>
  <ul class="facts">
    <li><b>Based in:</b> Muscat, Oman</li>
    <li><b>M.Tech:</b> Computer Science and Engineering, APJ Abdul Kalam Technological University (2024 – 2026)</li>
    <li><b>B.Tech:</b> Computer Science and Engineering, APJ Abdul Kalam Technological University (2020 – 2024)</li>
    <li><b>Resume:</b> <a href="Farsana Fathima NA - Data Analyst.pdf" target="_blank" rel="noopener">Download PDF</a></li>
  </ul>
</div></section>

<section id="contact" class="alt"><div class="wrap contact">
  <h2>Let's talk</h2>
  <p class="sub">I'm open to data analyst roles. Send me a message and I'll reply soon.</p>
  <div class="btns" style="justify-content:center">
    <a class="btn main" href="mailto:farsanafathima393@gmail.com">farsanafathima393@gmail.com</a>
    <a class="btn" href="https://linkedin.com/in/farsana-fathima-na-953332370" target="_blank" rel="noopener">LinkedIn</a>
    <a class="btn" href="tel:+96894988610">+968 9498 8610</a>
  </div>
</div></section>

<footer>&copy; <span id="yr"></span> Farsana Fathima NA</footer>

<dialog id="lb" aria-label="Project screenshots">
  <div class="lb-top"><b id="lbTitle"></b><button id="lbClose">Close</button></div>
  <div class="lb-img"><img id="lbImg" alt=""></div>
  <div class="lb-nav"><button id="lbPrev">Previous</button><span id="lbCap"></span><button id="lbNext">Next</button></div>
</dialog>

<script>
/* Project order = order shown on the site. Images are in the images/ folder. */
const projects = [
  {
    title: "Sales Overview Dashboard",
   
    summary: "A Power BI report on sales by month, zone, market, product type and customer type, ending with findings and recommendations.",
    tools: ["Power BI"],
    images: [
      ["images/sales-overview.jpg","Sales Overview"],
      ["images/sales-analysis.jpg","Overall Analysis"],
      ["images/sales-markets.jpg","Market-wise sales analysis"],
      ["images/sales-findings.jpg","Findings and Recommendations"]
    ],
    goal: "Show where sales come from and where the business should grow.",
    built: "KPI cards (total sales, profit, cost, margin, quantity), a monthly trend, zone, customer-type and product-type breakdowns, a year funnel, a market map and slicers for month, year, zone and customer type.",
    insights: [
      "April was the peak month. Sales were 4.74M in total with an 11.4% profit margin.",
      "The North zone led with about 3.56M, while South contributed about 0.51M.",
      "Brick and mortar made up 85.77% of sales. E-commerce made up 14.23%.",
      "Delhi NCR was the strongest market. Recommended: expand in weaker regions and grow e-commerce."
    ]
  },
  {
    title: "Payroll Analysis Dashboard",
   
    summary: "A Power BI payroll report for 130 employees covering cost, overtime and department statements for Aug 2026.",
    tools: ["Power BI"],
    images: [
      ["images/payroll-overview.jpg","Overview"],
      ["images/payroll-statement.jpg","Department-wise payroll statement"],
      ["images/payroll-summary.jpg","Payroll account summary"],
      ["images/payroll-employees.jpg","Employee details"]
    ],
    goal: "Give finance and HR one place to track payroll cost, overtime and department spend.",
    built: "A 4-page report with an overview, a department payroll statement, an account summary and an employee detail table, with a department filter.",
    insights: [
      "Gross payroll was 168.86K and net payroll 154.19K, up 2.71K from the previous month.",
      "IT had the highest gross payroll (39.52K) and the most overtime.",
      "Operations had the highest average cost per employee (1,553).",
      "Total overtime was 994 hours, costing 4.20K."
    ]
  },
  {
    title: "HR Recruitment Dashboard",
   
    summary: "A Tableau dashboard on hiring efficiency in 2026: funnel, sources and time to hire.",
    tools: ["Tableau"],
    images: [["images/hr-recruitment.jpg","HR Recruitment Dashboard"]],
    goal: "Understand which sources and departments produce hires, and where hiring slows down.",
    built: "KPI tiles, a recruitment funnel, source share and source analysis, department hiring, duration by department and filters for stage, role, department and source.",
    insights: [
      "319 candidates led to 27 hires: an 8.46% hire rate and 11.8 candidates per hire.",
      "The company website was the best source, with an 11.94% hire rate and 8 hires.",
      "IT had the most hires (10) and the longest time to final stage."
    ]
  },
  {
    title: "Employee Attendance Dashboard",

    summary: "An Excel dashboard on attendance, leave and lateness for 130 employees, with rule-based policy flags.",
    tools: ["Excel"],
    images: [
      ["images/attendance-dashboard.jpg","Employee Attendance Dashboard"],
      ["images/attendance-monthly.jpg","Monthly summary"],
      ["images/attendance-leave.jpg","Leave distribution per employee"],
      ["images/attendance-late.jpg","Punctuality watchlist"]
    ],
    goal: "Spot attendance problems early and flag employees who need follow-up.",
    built: "KPI cards, editable targets (95% attendance, flag below 92%, flag at 10+ late days), a risk-tier score, leave bands and a top 10 late arrivals list for Jan to Aug 2026.",
    insights: [
      "Attendance was 95.2% overall, above the 95% target, with a 4.0% late rate.",
      "Leave days peaked in August (151) and attendance was highest in July (95.8%).",
      "23 policy flags were raised. 16 employees were in the high-risk tier.",
      "13 employees (10%) took 13 or more leave days."
    ]
  },
  {
    title: "Project Performance Dashboard",
   
    summary: "A Power BI dashboard tracking 1,836 projects across 6 pipeline stages, with financial, physical and progress-difference views.",
    tools: ["Power BI"],
    images: [
      ["images/project-financial.jpg","Financial Progress view"],
      ["images/project-physical.jpg","Physical Progress view"],
      ["images/project-difference.jpg","Progress Difference view"]
    ],
    goal: "Give stakeholders real-time visibility of project progress, finances and risks.",
    built: "KPI cards, a project pipeline funnel, a risk donut chart, a project category chart and three switchable views (Financial Progress, Physical Progress, Progress Difference), driven by DAX measures and slicers.",
    insights: [
      "Tracked 1,836 projects through 6 pipeline stages, from DPR Approved (1,797) to Completed (367).",
      "Monitored ₹3,487 Cr in awarded value, with 24.80% financial progress and 89.57% bill clearance.",
      "Natural causes were the largest risk share (41.67% of 36 risks)."
    ]
  }
];

const grid = document.getElementById("grid");
const filters = document.getElementById("filters");
const lb = document.getElementById("lb"), lbImg = document.getElementById("lbImg");
let cur = {p:null,i:0};

function showImg(){
  const [src,cap] = cur.p.images[cur.i];
  lbImg.src = src; lbImg.alt = cur.p.title + ": " + cap;
  document.getElementById("lbTitle").textContent = cur.p.title;
  document.getElementById("lbCap").textContent = cap + " (" + (cur.i+1) + " of " + cur.p.images.length + ")";
  const one = cur.p.images.length === 1;
  document.getElementById("lbPrev").hidden = one;
  document.getElementById("lbNext").hidden = one;
  document.querySelector(".lb-img").scrollTop = 0;
}
function openLb(p){ cur = {p,i:0}; showImg(); lb.showModal(); }
document.getElementById("lbPrev").onclick = () => { cur.i = (cur.i - 1 + cur.p.images.length) % cur.p.images.length; showImg(); };
document.getElementById("lbNext").onclick = () => { cur.i = (cur.i + 1) % cur.p.images.length; showImg(); };
document.getElementById("lbClose").onclick = () => lb.close();
lb.addEventListener("click", e => { if (e.target === lb) lb.close(); });

projects.forEach((p, i) => {
  const card = document.createElement("article");
  card.className = "card";
  card.dataset.tools = p.tools.join("|");
  const thumb = p.images
    ? `<button class="thumb" aria-label="Open ${p.title} screenshots"><img src="${p.images[0][0]}" alt="${p.title} dashboard preview" loading="lazy"><span class="badge">${p.images.length} page${p.images.length>1?"s":""}</span></button>`
    : `<div class="thumb stat" style="--c1:${p.stat[2]};--c2:${p.stat[3]}"><b>${p.stat[0]}</b><span>${p.stat[1]}</span></div>`;
  card.innerHTML = `
    ${thumb}
    <div class="cbody">
      <h3>${p.title}</h3>
      <p>${p.summary}</p>
      <div class="tags">${p.tools.map(t => `<span class="tag">${t}</span>`).join("")}</div>
      <div class="more" id="more-${i}"><div>
        <dl>
          <dt>Goal</dt><dd>${p.goal}</dd>
          <dt>What I built</dt><dd>${p.built}</dd>
          <dt>Key findings</dt><dd><ul>${p.insights.map(x => `<li>${x}</li>`).join("")}</ul></dd>
        </dl>
      </div></div>
      <button class="toggle" aria-expanded="false" aria-controls="more-${i}">Show details</button>
      ${p.file ? `<div class="fileRow"><a class="dl" href="${p.file}" download>Download original file (.${p.file.split(".").pop()})</a></div>` : ""}
    </div>`;
  const btn = card.querySelector(".toggle");
  btn.addEventListener("click", () => {
    const open = card.classList.toggle("open");
    btn.setAttribute("aria-expanded", open);
    btn.textContent = open ? "Hide details" : "Show details";
  });
  const tb = card.querySelector("button.thumb");
  if (tb) tb.addEventListener("click", () => openLb(p));
  grid.appendChild(card);
});

["All", ...new Set(projects.flatMap(p => p.tools))].forEach((name, i) => {
  const b = document.createElement("button");
  b.className = "chip"; b.textContent = name;
  b.setAttribute("aria-pressed", i === 0);
  b.addEventListener("click", () => {
    filters.querySelectorAll(".chip").forEach(c => c.setAttribute("aria-pressed", c === b));
    grid.querySelectorAll(".card").forEach(c => {
      c.classList.toggle("hide", name !== "All" && !c.dataset.tools.split("|").includes(name));
    });
  });
  filters.appendChild(b);
});

document.getElementById("yr").textContent = new Date().getFullYear();
</script>
</body>
</html>
