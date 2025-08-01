<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Feature Test Page</title>
    <style>
        body { font-family: Arial, sans-serif; max-width: 800px; margin: 0 auto; padding: 20px; }
        .box { border: 1px solid #ccc; padding: 10px; margin: 10px 0; }
        .highlight { background-color: yellow; }
    </style>
</head>
<body>
    <header>
        <h1>HTML Feature Test Page</h1>
        <nav>
            <ul>
                <li><a href="#text">Text Elements</a></li>
                <li><a href="#media">Media</a></li>
                <li><a href="#forms">Forms</a></li>
                <li><a href="#tables">Tables</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="text" class="box">
            <h2>Text Elements</h2>
            <p>This is a regular paragraph with <strong>strong text</strong>, <em>emphasized text</em>, 
            <span class="highlight">highlighted span</span>, and a <a href="https://example.com">link</a>.</p>
            <h3>Headings</h3>
            <h1>Heading 1</h1>
            <h2>Heading 2</h2>
            <h3>Heading 3</h3>
            <h4>Heading 4</h4>
            <h5>Heading 5</h5>
            <h6>Heading 6</h6>
            <h3>Lists</h3>
            <ul>
                <li>Unordered list item 1</li>
                <li>Unordered list item 2</li>
                <li>Unordered list item 3</li>
            </ul>   
            <ol>
                <li>Ordered list item 1</li>
                <li>Ordered list item 2</li>
                <li>Ordered list item 3</li>
            </ol>
            <blockquote>This is a blockquote. It's used to highlight quoted text.</blockquote>
            <pre><code>// This is preformatted code
function test() {
    console.log("Hello World!");
}</code></pre>
        </section>
        <section id="media" class="box">
            <h2>Media Elements</h2>
            <img src="https://via.placeholder.com/150" alt="Placeholder image" width="150" height="150">          
            <figure>
                <img src="https://via.placeholder.com/300x100" alt="Wide placeholder">
                <figcaption>Figure with caption</figcaption>
            </figure>        
            <audio controls>
                <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>            
            <video width="320" height="240" controls>
                <source src="https://samplelib.com/lib/preview/mp4/sample-5s.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </section>
        <section id="forms" class="box">
            <h2>Form Elements</h2>
            <form action="/submit" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required><br><br>                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email"><br><br>             
                <label for="password">Password:</label>
                <input type="password" id="password" name="password"><br><br>              
                <label for="bio">Bio:</label>
                <textarea id="bio" name="bio" rows="4" cols="50"></textarea><br><br>    
                <label for="gender">Gender:</label>
                <select id="gender" name="gender">
                    <option value="male">Male</option>
                    <option value="female">Female</option>
                    <option value="other">Other</option>
                </select><br><br>   
                <fieldset>
                    <legend>Interests:</legend>
                    <input type="checkbox" id="sports" name="interest" value="sports">
                    <label for="sports">Sports</label><br>
                    <input type="checkbox" id="music" name="interest" value="music">
                    <label for="music">Music</label><br>
                    <input type="checkbox" id="books" name="interest" value="books">
                    <label for="books">Books</label><br>
                </fieldset>
                <fieldset>
                    <legend>Subscribe:</legend>
                    <input type="radio" id="yes" name="subscribe" value="yes">
                    <label for="yes">Yes</label><br>
                    <input type="radio" id="no" name="subscribe" value="no">
                    <label for="no">No</label><br>
                </fieldset>             
                <input type="submit" value="Submit">
                <input type="reset" value="Reset">
                <button type="button">Just a Button</button>
            </form>
        </section>
        <section id="tables" class="box">
            <h2>Tables</h2>
            <table border="1">
                <thead>
                    <tr>
                        <th>Name</th>
                        <th>Age</th>
                        <th>Occupation</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>John Doe</td>
                        <td>32</td>
                        <td>Developer</td>
                    </tr>
                    <tr>
                        <td>Jane Smith</td>
                        <td>28</td>
                        <td>Designer</td>
                    </tr>
                    <tr>
                        <td>Mike Johnson</td>
                        <td>41</td>
                        <td>Manager</td>
                    </tr>
                </tbody>
                <tfoot>
                    <tr>
                        <td colspan="2">Total People:</td>
                        <td>3</td>
                    </tr>
                </tfoot>
            </table>
        </section>
    </main>
    <footer class="box">
        <p>© 2023 HTML Test Page. All rights reserved.</p>
        <details>
            <summary>Additional Info</summary>
            <p>This page was created to test various HTML features.</p>
        </details>
    </footer>
</body>
</html>
