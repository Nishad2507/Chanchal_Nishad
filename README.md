# Chanchal_Nishad 
 * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: 'Segoe UI', sans-serif;
    line-height: 1.6;
    background: #f5f5f5;
}
.navbar {
    display: flex;
    justify-content: space-between;
    padding: 1rem 2rem;
    background: #dde3a7;
}

.nav-links {
    display: flex;
    gap: 2rem;
    list-style: none;
}
.search-btn, .cta, .explore-btn, .learn-btn, .view-btn, .read-btn {
    padding: 10px 16px;
    background: #333;
    color: white;
    border: none;
    cursor: pointer;
}
.hero {
    display: flex;
    justify-content: space-between;
    background: #cfd49c;
    padding: 4rem 2rem;
}
.hero-left h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
}
.hero-right img {
    width: 300px;
}
.features, .mission, .highlight, .services, .ready, .faq, .blog {
    padding: 4rem 2rem;
    text-align: center;
}
.mission {
    background: #6c5c5c;
    color: white;
}
.mission-flex {
    display: flex;
    justify-content: center;
    gap: 2rem;
    margin-bottom: 3rem;
}
.stats {
    display: flex;
    justify-content: center;
    gap: 4rem;
}
.highlight {
    display: flex;
    justify-content: space-around;
    align-items: center;
    background: #6c5c5c;
    color: white;
}
.services .cards {
    display: flex;
    justify-content: space-around;
    margin: 2rem 0;
}
.card {
    width: 30%;
    padding: 2rem;
    border-radius: 12px;
    color: #000;
}
.blue { background: #cfe2ff; }
.orange { background: #ffe0b2; }
.green { background: #d4edda; }
.ready {
    background: #3f704d;
    color: white;
    padding: 3rem 2rem;
}
.accordion details {
    margin-bottom: 1rem;
    background: #f9f9f9;
    padding: 1rem;
    border: 1px solid #ccc;
    border-radius: 8px;from flask import Flask, render_template

app = Flask(_name_)

@app.route('/')
def home():
    return render_template("index.html")

if _name_ == '_main_':
    app.run(debug=True)
}
h1{
        font-size: 30px;
 from flask import Flask, render_template

app = Flask(_name_)

@app.route('/')
def home():
    return render_template("index.html")

if _name_ == '_main_':
    app.run(debug=True)
