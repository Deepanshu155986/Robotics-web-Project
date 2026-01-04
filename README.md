/* comment section by ayush */
body {
    background: radial-gradient(circle at top, #0f172a, #020617);
    color: #e5e7eb;
}

/* Main Section */
.news-section {
    width: 90%;
    max-width: 1200px;
    margin: auto;
    padding: 50px 0;
}

.news-section h1 {
    text-align: center;
    font-size: 42px;
    margin-bottom: 30px;
}

/* Filters */
.filters {
    display: flex;
    justify-content: center;
    gap: 15px;
    margin-bottom: 40px;
    flex-wrap: wrap;
}

.filters button {
    background: #020617;
    border: 1px solid #1e293b;
    color: #cbd5f5;
    padding: 10px 18px;
    border-radius: 25px;
    cursor: pointer;
    transition: 0.3s;
}

.filters button.active,
.filters button:hover {
    background: #22d3ee;
    color: #020617;
}

/* News Grid */
.news-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
    gap: 30px;
}

/* Card */
.news-card {
    background: rgba(15, 23, 42, 0.8);
    border: 1px solid #1e293b;
    border-radius: 14px;
    padding: 25px;
    transition: 0.3s;
}

.news-card:hover {
    transform: translateY(-6px);
    box-shadow: 0 0 25px rgba(34, 211, 238, 0.15);
}

/* Tags */
.tag {
    display: inline-block;
    font-size: 12px;
    padding: 5px 10px;
    border-radius: 20px;
    margin-bottom: 12px;
}

.club { background: #22d3ee33; color: #22d3ee; }
.tech { background: #38bdf833; color: #38bdf8; }
.research { background: #a78bfa33; color: #a78bfa; }
.competition { background: #facc1533; color: #facc15; }

/* Text */
.news-card h3 {
    font-size: 20px;
    margin-bottom: 8px;
}

.meta {
    font-size: 13px;
    color: #94a3b8;
    margin-bottom: 12px;
}

.desc {
    font-size: 15px;
    line-height: 1.6;
    color: #cbd5f5;
    margin-bottom: 15px;
}

.news-card a {
    color: #22d3ee;
    text-decoration: none;
    font-weight: 500;
}

/* Newsletter */
.newsletter {
    margin-top: 70px;
    padding: 40px;
    background: linear-gradient(135deg, #020617, #0f172a);
    border-radius: 16px;
    text-align: center;
    border: 1px solid #1e293b;
}

.newsletter h2 {
    font-size: 28px;
    margin-bottom: 10px;
}

.newsletter p {
    color: #94a3b8;
    margin-bottom: 25px;
}

.subscribe-box {
    display: flex;
    justify-content: center;
    gap: 10px;
    flex-wrap: wrap;
}

.subscribe-box input {
    padding: 12px;
    width: 260px;
    border-radius: 8px;
    border: 1px solid #1e293b;
    background: #020617;
    color: white;
}

.subscribe-box button {
    padding: 12px 22px;
    border-radius: 8px;
    border: none;
    background: #22d3ee;
    color: #020617;
    font-weight: bold;
    cursor: pointer;
}











