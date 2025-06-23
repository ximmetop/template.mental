<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Informática Mental</title>
    <style>
        /* Reset and Base Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            background: #f4f4f4;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Header and Navigation */
        header {
            background: #2c3e50;
            color: #fff;
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        nav ul li a:hover {
            color: #3498db;
        }

        /* Sections */
        section {
            padding: 60px 0;
        }

        section h1, section h2, section h3, section h4, section h5, section h6 {
            margin-bottom: 20px;
        }

        section#intro {
            background: #3498db;
            color: #fff;
            text-align: center;
        }

        section#work, section#about {
            background: #fff;
        }

        section#contact {
            background: #ecf0f1;
        }

        section#elements {
            background: #fff;
        }

        /* Contact Form */
        form {
            display: grid;
            gap: 15px;
            max-width: 600px;
            margin: 0 auto;
        }

        input, textarea, select, button {
            padding: 10px;
            width: 100%;
            border: 1px solid #ddd;
            border-radius: 4px;
        }

        button {
            background: #3498db;
            color: #fff;
            border: none;
            cursor: pointer;
        }

        button:hover {
            background: #2980b9;
        }

        /* Elements Styling */
        .elements-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .elements-grid > div {
            background: #f9f9f9;
            padding: 20px;
            border-radius: 4px;
        }

        /* Tables */
        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 20px;
        }

        table, th, td {
            border: 1px solid #ddd;
        }

        th, td {
            padding: 10px;
            text-align: left;
        }

        /* Buttons */
        .button {
            display: inline-block;
            padding: 10px 20px;
            margin: 5px;
            background: #3498db;
            color: #fff;
            text-decoration: none;
            border-radius: 4px;
        }

        .button:hover {
            background: #2980b9;
        }

        .button.disabled {
            background: #ccc;
            cursor: not-allowed;
        }

        /* Icons */
        .social-icons a {
            margin: 0 10px;
            color: #3498db;
            text-decoration: none;
            font-size: 1.5rem;
        }

        .social-icons a:hover {
            color: #2980b9;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                gap: 10px;
            }

            .elements-grid {
                grid-template-columns: 1fr;
            }
        }

        /* Footer */
        footer {
            background: #2c3e50;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <nav class="container">
            <h1>Informática Mental</h1>
            <ul>
                <li><a href="#intro">Intro</a></li>
                <li><a href="#work">Work</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#elements">Elements</a></li>
            </ul>
        </nav>
    </header>

    <!-- Intro Section -->
    <section id="intro" class="container">
        <h1>Intro</h1>
        <p>Aenean ornare velit lacus, ac varius enim ullamcorper eu. Proin aliquam facilisis ante interdum congue. Integer mollis, nisl amet convallis, porttitor magna ullamcorper, amet egestas mauris. Ut magna finibus nisi nec lacinia. Nam maximus erat id euismod egestas. By the way, check out my <a href="#work">awesome work</a>.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis dapibus rutrum facilisis. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Etiam tristique libero eu nibh porttitor fermentum. Nullam venenatis erat id vehicula viverra. Nunc ultrices eros ut ultricies condimentum. Mauris risus lacus, blandit sit amet venenatis non, bibendum vitae dolor. Nunc lorem mauris, fringilla in aliquam at, euismod in lectus. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. In non lorem sit amet elit placerat maximus. Pellentesque aliquam maximus risus, vel sed vehicula.</p>
    </section>

    <!-- Work Section -->
    <section id="work" class="container">
        <h1>Work</h1>
        <p>Adipiscing magna sed dolor elit. Praesent eleifend dignissim arcu, at eleifend sapien imperdiet ac. Aliquam erat volutpat. Praesent urna nisi, fringila lorem et vehicula lacinia quam. Integer sollicitudin mauris nec lorem luctus ultrices.</p>
        <p>Nullam et orci eu lorem consequat tincidunt vivamus et sagittis libero. Mauris aliquet magna magna sed nunc rhoncus pharetra. Pellentesque condimentum sem. In efficitur ligula tate urna. Maecenas laoreet massa vel lacinia pellentesque lorem ipsum dolor. Nullam et orci eu lorem consequat tincidunt. Vivamus et sagittis libero. Mauris aliquet magna magna sed nunc rhoncus amet feugiat tempus.</p>
    </section>

    <!-- About Section -->
    <section id="about" class="container">
        <h1>About</h1>
        <p>Lorem ipsum dolor sit amet, consectetur et adipiscing elit. Praesent eleifend dignissim arcu, at eleifend sapien imperdiet ac. Aliquam erat volutpat. Praesent urna nisi, fringila lorem et vehicula lacinia quam. Integer sollicitudin mauris nec lorem luctus ultrices. Aliquam libero et malesuada fames ac ante ipsum primis in faucibus. Cras viverra ligula sit amet ex mollis mattis lorem ipsum dolor sit amet.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="container">
        <h1>Contact</h1>
        <form>
            <label for="name">Name</label>
            <input type="text" id="name" placeholder="Jane Doe" required>

            <label for="email">Email</label>
            <input type="email" id="email" placeholder="jane@untitled.tld" required>

            <label for="category">Category</label>
            <select id="category">
                <option value="">-</option>
                <option value="low">Low</option>
                <option value="high">High</option>
            </select>

            <label>
                <input type="checkbox"> Email me a copy
            </label>

            <label>
                <input type="checkbox"> Not a robot
            </label>

            <label for="message">Message</label>
            <textarea id="message" placeholder="Enter your message" rows="5"></textarea>

            <button type="submit">Send Message</button>
        </form>
        <div class="social-icons">
            <a href="#">Twitter</a>
            <a href="#">Facebook</a>
            <a href="#">Instagram</a>
            <a href="#">GitHub</a>
        </div>
    </section>

    <!-- Elements Section -->
    <section id="elements" class="container">
        <h1>Elements</h1>
        <div class="elements-grid">
            <!-- Text -->
            <div>
                <h2>Text</h2>
                <p>This is <b>bold</b> and this is <strong>strong</strong>. This is <i>italic</i> and this is <em>emphasized</em>. This is <sup>superscript</sup> text and this is <sub>subscript</sub> text. This is <u>underlined</u> and this is code: <code>for (;;) { ... }</code>. Finally, <a href="#">this is a link</a>.</p>
            </div>

            <!-- Headings -->
            <div>
                <h2>Heading Level 2</h2>
                <h3>Heading Level 3</h3>
                <h4>Heading Level 4</h4>
                <h5>Heading Level 5</h5>
                <h6>Heading Level 6</h6>
            </div>

            <!-- Blockquote -->
            <div>
                <h2>Blockquote</h2>
                <blockquote>Fringilla nisl. Donec accumsan interdum nisi, quis adipiscing accumsan adipiscing eu felis iaculis volutpat ac adipiscing accumsan faucibus. Vestibulum ante ipsum primis in faucibus lorem ipsum dolor sit amet.</blockquote>
            </div>

            <!-- Preformatted -->
            <div>
                <h2>Preformatted</h2>
                <pre>
i = 0;

while (!deck.isInOrder()) {
    print 'Iteration " + i;
    deck.shuffle();
    i++;
}

print 'It took ' + i + ' iterations to sort the deck.';
                </pre>
            </div>

            <!-- Lists -->
            <div>
                <h2>Lists</h2>
                <h3>Unordered</h3>
                <ul>
                    <li>Dolor pulvinar etiam.</li>
                    <li>Sagittist adipiscing.</li>
                    <li>Felis enim feugiat.</li>
                </ul>

                <h3>Alternate</h3>
                <ul>
                    <li>Dolor pulvinar etiam.</li>
                    <li>Sagittist adipiscing.</li>
                    <li>Felis enim feugiat.</li>
                </ul>

                <h3>Ordered</h3>
                <ol>
                    <li>Dolor pulvinar etiam.</li>
                    <li>Etiam vel felis viverra.</li>
                    <li>Felis enim feugiat.</li>
                    <li>Dolor pulvinar etiam.</li>
                    <li>Etiam vel felis lorem.</li>
                    <li>Felis enim et feugiat.</li>
                </ol>
            </div>

            <!-- Icons -->
            <div>
                <h2>Icons</h2>
                <div class="social-icons">
                    <a href="#">Twitter</a>
                    <a href="#">Facebook</a>
                    <a href="#">Instagram</a>
                    <a href="#">GitHub</a>
                </div>
            </div>

            <!-- Actions -->
            <div>
                <h2>Actions</h2>
                <a href="#" class="button">Default</a>
                <a href="#" class="button">Default</a>
                <a href="#" class="button">Default</a>
                <a href="#" class="button">Default</a>
            </div>

            <!-- Tables -->
            <div>
                <h2>Table</h2>
                <h3>Default</h3>
                <table>
                    <thead>
                        <tr>
                            <th>Name</th>
                            <th>Description</th>
                            <th>Price</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>Item One</td>
                            <td>Ante turpis integer aliquet porttitor.</td>
                            <td>29.99</td>
                        </tr>
                        <tr>
                            <td>Item Two</td>
                            <td>Vis ac commodo adipiscing arcu aliquet.</td>
                            <td>19.99</td>
                        </tr>
                        <tr>
                            <td>Item Three</td>
                            <td>Morbi faucibus arcu accumsan lorem.</td>
                            <td>29.99</td>
                        </tr>
                        <tr>
                            <td>Item Four</td>
                            <td>Vitae integer tempus condimentum.</td>
                            <td>19.99</td>
                        </tr>
                        <tr>
                            <td>Item Five</td>
                            <td>Ante turpis integer aliquet porttitor.</td>
                            <td>29.99</td>
                        </tr>
                        <tr>
                            <td colspan="2"></td>
                            <td>100.00</td>
                        </tr>
                    </tbody>
                </table>

                <h3>Alternate</h3>
                <table>
                    <thead>
                        <tr>
                            <th>Name</th>
                            <th>Description</th>
                            <th>Price</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>Item One</td>
                            <td>Ante turpis integer aliquet porttitor.</td>
                            <td>29.99</td>
                        </tr>
                        <tr>
                            <td>Item Two</td>
                            <td>Vis ac commodo adipiscing arcu aliquet.</td>
                            <td>19.99</td>
                        </tr>
                        <tr>
                            <td>Item Three</td>
                            <td>Morbi faucibus arcu accumsan lorem.</td>
                            <td>29.99</td>
                        </tr>
                        <tr>
                            <td>Item Four</td>
                            <td>Vitae integer tempus condimentum.</td>
                            <td>19.99</td>
                        </tr>
                        <tr>
                            <td>Item Five</td>
                            <td>Ante turpis integer aliquet porttitor.</td>
                            <td>29.99</td>
                        </tr>
                        <tr>
                            <td colspan="2"></td>
                            <td>100.00</td>
                        </tr>
                    </tbody>
                </table>
            </div>

            <!-- Buttons -->
            <div>
                <h2>Buttons</h2>
                <a href="#" class="button">Primary</a>
                <a href="#" class="button">Default</a>
                <a href="#" class="button">Default</a>
                <a href="#" class="button">Small</a>
                <a href="#" class="button">Icon</a>
                <a href="#" class="button">Icon</a>
                <a href="#" class="button disabled">Disabled</a>
                <a href="#" class="button disabled">Disabled</a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>© Informática Mental. Design: <a href="https://html5up.net">HTML5 UP</a>. Released under the <a href="https://creativecommons.org/licenses/by/3.0/">Creative Commons License</a>.</p>
    </footer>
</body>
</html>
