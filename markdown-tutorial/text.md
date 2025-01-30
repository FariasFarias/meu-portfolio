<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Markdown Block</title>
    <style>
        .markdown {
            background-color: #f6f8fa;
            border: 1px solid #d1d5da;
            border-radius: 6px;
            padding: 16px;
            font-family: "Courier New", monospace;
            line-height: 1.5;
            white-space: pre-wrap;
            word-wrap: break-word;
        }
        
        .markdown h1 {
            font-size: 1.5em;
            border-bottom: 2px solid #ccc;
            padding-bottom: 5px;
        }

        .markdown h2 {
            font-size: 1.3em;
            border-bottom: 1px solid #ddd;
            padding-bottom: 3px;
        }

        .markdown code {
            background-color: #eaecef;
            padding: 2px 5px;
            border-radius: 3px;
            font-family: "Courier New", monospace;
        }

        .markdown pre {
            background-color: #282c34;
            color: #ffffff;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }

        .markdown blockquote {
            border-left: 4px solid #ccc;
            padding-left: 10px;
            color: #666;
            margin: 10px 0;
        }

        .markdown ul {
            padding-left: 20px;
        }

        .markdown li {
            margin-bottom: 5px;
        }
    </style>
</head>
<body>

    <div class="markdown">
        <h1>Título H1</h1>
        <h2>Título H2</h2>
        <p>Este é um bloco de Markdown dentro de uma <code>div</code>.</p>
        <blockquote>Isso é uma citação em Markdown.</blockquote>
        <pre><code>console.log("Olá, mundo!");</code></pre>
        <ul>
            <li>Item 1</li>
            <li>Item 2</li>
            <li>Item 3</li>
        </ul>
    </div>

</body>
</html>
