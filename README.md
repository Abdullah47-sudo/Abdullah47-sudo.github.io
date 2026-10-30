
NAME = "Muhammad Abdullah"
USER = "Abdullah47-sudo"
UNIVERSITY = "UCP"
EMAIL = "abdullahjv791@gmail.com"           
BASE_URL = f"https://{USER.lower()}.github.io"

TAGLINE = "Software Engineering student who enjoys solving problems and writing clean Java."
ABOUT = [
    ("Student", f"Third-semester Software Engineering student at {UNIVERSITY}."),
    ("Problem solver", "I like breaking problems down and practising data structures and algorithms."),
    ("Backend coder", "I have hands-on experience with backend coding in Java."),
    ("Always learning", "I am improving my fundamentals and writing cleaner code every week."),
]
SKILLS = {
    "Language": ["Java"],
    "Tools": ["IntelliJ IDEA", "VS Code", "GitHub"],
    "Concepts": ["Problem Solving", "Data Structures & Algorithms", "Object-Oriented Programming"],
}
PROJECTS = [
    # ("Library Manager", "Console app in Java using OOP.", f"https://github.com/{USER}/library-manager"),
]
HASHTAGS = ["Java", "SoftwareEngineering", "BackendDeveloper", "ProblemSolving",
            "DataStructures", "Algorithms", "OOP", "Student", "Developer", "GitHub"]
KEYWORDS = [NAME, USER, "Java developer", "software engineering student", f"{UNIVERSITY} student",
            "backend developer", "problem solving", "data structures and algorithms",
            "Java projects", "fresher developer portfolio"]
# --------------------------------------------------------------------

DESC = (f"{NAME} is a software engineering student at {UNIVERSITY} building backend projects in Java. "
        "Skills: Java, problem solving, data structures and algorithms, OOP.")

HERO_SVG = """<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 440" role="img" aria-label="Laptop with code and a cup of Java coffee">
<defs><linearGradient id="g" x1="0" y1="0" x2="1" y2="1"><stop offset="0" stop-color="#16294a"/><stop offset="1" stop-color="#0b1730"/></linearGradient></defs>
<rect width="640" height="440" rx="28" fill="#e9eef7"/>
<circle cx="540" cy="80" r="110" fill="#f6b26b" opacity=".35"/><circle cx="90" cy="380" r="90" fill="#7aa7ff" opacity=".25"/>
<rect x="110" y="70" width="360" height="230" rx="14" fill="url(#g)"/>
<rect x="128" y="88" width="324" height="194" rx="6" fill="#0b1730"/>
<g font-family="monospace" font-size="14"><text x="146" y="118" fill="#f6b26b">public class</text><text x="246" y="118" fill="#9fd0ff"> Me {</text>
<text x="164" y="146" fill="#8ee3b0">String role =</text><text x="270" y="146" fill="#ffd98a"> "Student";</text>
<text x="164" y="174" fill="#8ee3b0">int solved =</text><text x="256" y="174" fill="#ffd98a"> 100+;</text>
<text x="164" y="202" fill="#8ee3b0">learn();</text><text x="146" y="230" fill="#9fd0ff">}</text></g>
<rect x="150" y="248" width="60" height="6" rx="3" fill="#f6b26b"/>
<path d="M70 300 H510 L486 326 H94 Z" fill="#c4cfe3"/><rect x="94" y="326" width="392" height="10" rx="5" fill="#a9b8d3"/>
<g transform="translate(500 210)"><path d="M0 40 H88 L80 130 Q78 148 60 148 H28 Q10 148 8 130 Z" fill="#ffffff" stroke="#10203a" stroke-width="5"/>
<path d="M88 58 Q122 60 118 92 Q114 120 82 118" fill="none" stroke="#10203a" stroke-width="5"/>
<rect x="8" y="48" width="72" height="20" fill="#e76f00" opacity=".9"/>
<path d="M28 28 Q18 12 30 0 Q40 -12 32 -28" fill="none" stroke="#7a8aa8" stroke-width="5" stroke-linecap="round"/>
<path d="M58 28 Q48 12 60 0 Q70 -12 62 -28" fill="none" stroke="#7a8aa8" stroke-width="5" stroke-linecap="round"/></g>
</svg>"""

FAVICON_SVG = """<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 64 64"><rect width="64" height="64" rx="14" fill="#10203a"/>
<text x="32" y="43" font-family="Arial" font-weight="700" font-size="30" text-anchor="middle" fill="#f6b26b">MA</text></svg>"""

CSS = """
:root{--ink:#10203a;--muted:#51617d;--bg:#f3f6fb;--card:#fff;--line:#d9e1ef;--accent:#e76f00;--deep:#16294a}
*{box-sizing:border-box}html{scroll-behavior:smooth}
body{margin:0;font:17px/1.65 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;color:var(--ink);background:var(--bg)}
a{color:var(--deep)}a:focus-visible,button:focus-visible{outline:3px solid var(--accent);outline-offset:3px}
.wrap{max-width:1000px;margin:0 auto;padding:0 22px}
header.top{background:#fff;border-bottom:1px solid var(--line);position:sticky;top:0;z-index:5}
header.top .wrap{display:flex;justify-content:space-between;align-items:center;min-height:60px;flex-wrap:wrap;gap:8px}
.brand{font-weight:700;text-decoration:none;color:var(--ink)}
nav a{margin-left:18px;text-decoration:none;color:var(--muted);font-weight:500}nav a:hover{color:var(--accent)}
.hero{padding:56px 0 40px}.hero .wrap{display:grid;grid-template-columns:1.1fr 1fr;gap:36px;align-items:center}
h1{font-size:clamp(2.1rem,5vw,3.2rem);line-height:1.1;margin:0 0 14px}
.lead{color:var(--muted);font-size:1.15rem;max-width:34ch;margin:0 0 24px}
.btn{display:inline-block;padding:11px 20px;border-radius:10px;text-decoration:none;font-weight:600;margin:0 10px 10px 0}
.btn.main{background:var(--accent);color:#fff}.btn.alt{border:2px solid var(--deep);color:var(--deep)}
.hero img{width:100%;height:auto;display:block;border-radius:28px}
section{padding:44px 0}h2{font-size:1.7rem;margin:0 0 22px}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px}
.card{background:var(--card);border:1px solid var(--line);border-radius:14px;padding:20px}
.card h3{margin:0 0 6px;font-size:1.05rem}.card p{margin:0;color:var(--muted)}
.skills .row{display:flex;flex-wrap:wrap;gap:10px;align-items:center;margin-bottom:14px}
.skills b{min-width:100px}.chip{background:#fff;border:1px solid var(--line);border-radius:999px;padding:5px 14px;font-size:.95rem}
.empty{border-style:dashed}
footer{background:var(--deep);color:#dbe5f7;padding:36px 0;margin-top:30px}
footer a{color:#ffd98a}.tags{display:flex;flex-wrap:wrap;gap:8px;margin:14px 0 0}.tags span{font-size:.9rem;opacity:.85}
@media(max-width:760px){.hero .wrap{grid-template-columns:1fr}nav a{margin:0 14px 0 0}}
"""


def build_html():
    about = "".join(f'<div class="card"><h3>{escape(t)}</h3><p>{escape(d)}</p></div>' for t, d in ABOUT)
    skills = "".join(
        f'<div class="row"><b>{escape(k)}</b>' + "".join(f'<span class="chip">{escape(s)}</span>' for s in v) + "</div>"
        for k, v in SKILLS.items())
    if PROJECTS:
        projects = "".join(
            f'<div class="card"><h3><a href="{escape(l)}">{escape(t)}</a></h3><p>{escape(d)}</p></div>'
            for t, d, l in PROJECTS)
    else:
        projects = (f'<div class="card empty"><h3>Projects are on the way</h3>'
                    f'<p>I am building Java projects and publishing them on '
                    f'<a href="https://github.com/{USER}">my GitHub</a>.</p></div>')
    tags = "".join(f"<span>#{escape(h)}</span>" for h in HASHTAGS)
    person = {
        "@context": "https://schema.org", "@type": "Person", "name": NAME, "alternateName": USER,
        "url": BASE_URL + "/", "image": BASE_URL + "/assets/hero.svg",
        "jobTitle": "Software Engineering Student", "description": DESC,
        "affiliation": {"@type": "CollegeOrUniversity", "name": UNIVERSITY},
        "knowsAbout": ["Java", "Problem Solving", "Data Structures", "Algorithms", "Object-Oriented Programming"],
        "sameAs": [f"https://github.com/{USER}"],
    }
    return f"""<!doctype html>
<html lang="en"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>{escape(NAME)} | Java &amp; Software Engineering Student</title>
<meta name="description" content="{escape(DESC)}">
<meta name="keywords" content="{escape(', '.join(KEYWORDS))}">
<meta name="author" content="{escape(NAME)}">
<meta name="robots" content="index, follow">
<link rel="canonical" href="{BASE_URL}/">
<link rel="icon" href="assets/favicon.svg" type="image/svg+xml">
<meta property="og:type" content="website"><meta property="og:title" content="{escape(NAME)} | Software Engineering Student">
<meta property="og:description" content="{escape(DESC)}"><meta property="og:url" content="{BASE_URL}/">
<meta property="og:image" content="{BASE_URL}/assets/hero.svg"><meta name="twitter:card" content="summary_large_image">
<script type="application/ld+json">{json.dumps(person)}</script>
<style>{CSS}</style></head><body>
<header class="top"><div class="wrap"><a class="brand" href="#top">{escape(NAME)}</a>
<nav aria-label="Main"><a href="#about">About</a><a href="#skills">Skills</a><a href="#projects">Projects</a><a href="#contact">Contact</a></nav></div></header>
<main id="top">
<div class="hero"><div class="wrap"><div>
<h1>Hi, I'm {escape(NAME)}</h1><p class="lead">{escape(TAGLINE)}</p>
<a class="btn main" href="https://github.com/{USER}">View my GitHub</a><a class="btn alt" href="#contact">Get in touch</a></div>
<img src="assets/hero.svg" alt="Illustration of a laptop showing Java code next to a cup of coffee" width="640" height="440"></div></div>
<section id="about"><div class="wrap"><h2>About me</h2><div class="grid">{about}</div></div></section>
<section id="skills" class="skills"><div class="wrap"><h2>Skills</h2>{skills}</div></section>
<section id="projects"><div class="wrap"><h2>Projects</h2><div class="grid">{projects}</div></div></section>
</main>
<footer id="contact"><div class="wrap"><h2 style="color:#fff">Contact</h2>
<p>Email: <a href="mailto:{escape(EMAIL)}">{escape(EMAIL)}</a><br>GitHub: <a href="https://github.com/{USER}">github.com/{USER}</a></p>
<div class="tags">{tags}</div><p style="opacity:.7;margin-top:22px">&copy; {date.today().year} {escape(NAME)}</p></div></footer>
</body></html>"""


def main():
    out = Path("site")
    (out / "assets").mkdir(parents=True, exist_ok=True)
    (out / "index.html").write_text(build_html(), encoding="utf-8")
    (out / "assets" / "hero.svg").write_text(HERO_SVG, encoding="utf-8")
    (out / "assets" / "favicon.svg").write_text(FAVICON_SVG, encoding="utf-8")
    (out / "robots.txt").write_text(f"User-agent: *\nAllow: /\nSitemap: {BASE_URL}/sitemap.xml\n", encoding="utf-8")
    (out / "sitemap.xml").write_text(
        '<?xml version="1.0" encoding="UTF-8"?>\n<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">'
        f"<url><loc>{BASE_URL}/</loc><lastmod>{date.today().isoformat()}</lastmod></url></urlset>\n",
        encoding="utf-8")
    print("Done! Open site/index.html in your browser.")


if __name__ == "__main__":
    main()
