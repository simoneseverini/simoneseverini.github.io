<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>

    <script>
    window.MathJax = {
      tex: {
        inlineMath: [['$', '$'], ['\\(', '\\)']]
      },
      chtml: {
        scale: 1,                      
        minScale: .5,                  
        matchFontHeight: true         
      }
    };
    </script>
    <script type="text/javascript" id="MathJax-script" async
      src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
    </script>

    <style>
        /* --- VARIABLES --- */
        :root {
            --bg: #f4f4f4;
            --card-bg: #ffffff;
            --text: #111;
            --meta: #666;
            --accent: #0056b3;
            --badge-bg: #eef3f8;
            --border: #eee;
            --code-bg: #f8f8f8;
        }

        /* --- GLOBAL LAYOUT --- */
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            padding: 0;
            background-color: var(--bg);
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            color: var(--text);
            line-height: 1.6;
            overflow-x: hidden;
        }

        /* --- CONTAINER --- */
        .diary-container {
            max-width: 850px;
            margin: 0 auto;
            padding: 50px 20px 100px 20px;
            width: 100%;
        }

        /* --- ENTRY CARD STYLE --- */
        .entry {
            background: var(--card-bg);
            padding: 40px;
            border-radius: 6px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.04);
            margin-bottom: 30px;
            border: 1px solid transparent;
            transition: border-color 0.2s ease;
            overflow-wrap: break-word;
        }

        ol {
            margin: 0;
            padding-left: 20px;
            color: #444;
        }

        li {
            margin-bottom: 8px;
        }

        /* --- MOBILE OPTIMIZATION --- */
        @media (max-width: 600px) {
            .diary-container {
                padding: 20px 10px 100px 10px;
            }

            .entry {
                padding: 25px 15px;
            }
        }
    </style>
</head>
<body>

  <div class="diary-container">
    <div class="entry">
        <ol>
            <li>&nbsp;</li>
            <li>&nbsp;</li>
            <li>&nbsp;</li>
        </ol>
    </div>
  </div>

</body>
</html>
