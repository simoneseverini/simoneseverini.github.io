<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name | Researcher & Developer</title>
    <style>
        :root {
            --bg: #fdfdfd;
            --text: #333;
            --sidebar-bg: #f8f8f8;
            --accent: #0056b3;
        }
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            margin: 0; display: flex; line-height: 1.6; color: var(--text); background: var(--bg);
        }
        /* Sidebar */
        aside {
            width: 280px; height: 100vh; position: sticky; top: 0;
            background: var(--sidebar-bg); border-right: 1px solid #eee;
            padding: 40px 30px; box-sizing: border-box;
        }
        aside h1 { font-size: 1.5rem; margin-bottom: 0.5rem; font-weight: 600; }
        aside p { font-size: 0.9rem; color: #666; margin-bottom: 2rem; }
        nav a { display: block; text-decoration: none; color: var(--text); font-weight: 500; margin: 10px 0; }
        nav a:hover { color: var(--accent); }
        
        /* Main Content */
        main { flex: 1; max-width: 800px; padding: 60px 50px; }
        section { margin-bottom: 3rem; }
        h2 { border-bottom: 1px solid #eee; padding-bottom: 5px; font-weight: 500; }
        .item { margin-bottom: 1.5rem; }
        .date { color: #888; font-size: 0.85rem; }

        @media (max-width: 768px) {
            body { flex-direction: column; }
            aside { width: 100%; height: auto; position: relative; }
        }
    </style>
</head>
<body>
    <aside>
        <h1>Your Name</h1>
        <p>A concise bio: nuanced, direct, and focused on the essentials.</p>
        <nav>
            <a href="#about">About</a>
            <a href="#research">Research</a>
            <a href="#blog">Blog</a>
            <a href="mailto:you@example.com">Email</a>
        </nav>
    </aside>

    <main>
        <section id="about">
            <h2>About</h2>
            <p>Describe your work here. Ground your abstractions in vivid detail—mention the specific projects, the textures of the problems you solve, and the silences you aim to fill.</p>
        </section>

        <section id="research">
            <h2>Publications</h2>
            <div class="item">
                <strong>The Logic of Silence</strong> <span class="date">(2025)</span><br>
                <em>Conference on Concrete Abstractions.</em>
            </div>
        </section>
    </main>
</body>
</html>
