<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>English Level Test</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 20px;
            background-color: #f4f4f9;
        }
        .container {
            max-width: 600px;
            margin: 0 auto;
            background: #ffffff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
            color: #333333;
        }
        .question {
            margin-bottom: 15px;
        }
        .question p {
            margin: 0;
            font-size: 16px;
        }
        .options {
            margin-top: 10px;
        }
        .options label {
            display: block;
            margin-bottom: 8px;
            cursor: pointer;
        }
        .submit-btn {
            display: block;
            width: 100%;
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }
        .submit-btn:hover {
            background-color: #45a049;
        }
        .result {
            margin-top: 20px;
            text-align: center;
            font-size: 18px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>English Level Test</h1>
        <form id="testForm">
            <div class="question">
                <p>1. Choose the correct sentence:</p>
                <div class="options">
                    <label><input type="radio" name="q1" value="1"> She go to school every day.</label>
                    <label><input type="radio" name="q1" value="2"> She goes to school every day.</label>
                    <label><input type="radio" name="q1" value="3"> She going to school every day.</label>
                </div>
            </div>
            <div class="question">
                <p>2. Fill in the blank: "I _____ a book right now."
                </p>
                <div class="options">
                    <label><input type="radio" name="q2" value="1"> reads</label>
                    <label><input type="radio" name="q2" value="2"> read</label>
                    <label><input type="radio" name="q2" value="3"> am reading</label>
                </div>
            </div>
            <div class="question">
                <p>3. Select the correct synonym for "happy":</p>
                <div class="options">
                    <label><input type="radio" name="q3" value="1"> Sad</label>
                    <label><input type="radio" name="q3" value="2"> Joyful</label>
                    <label><input type="radio" name="q3" value="3"> Angry</label>
                </div>
            </div>
            <div class="question">
                <p>4. Which word is a noun?</p>
                <div class="options">
                    <label><input type="radio" name="q4" value="1"> Quickly</label>
                    <label><input type="radio" name="q4" value="2"> Happiness</label>
                    <label><input type="radio" name="q4" value="3"> Run</label>
                </div>
            </div>
            <div class="question">
                <p>5. Choose the correct past tense of "go":</p>
                <div class="options">
                    <label><input type="radio" name="q5" value="1"> Goed</label>
                    <label><input type="radio" name="q5" value="2"> Went</label>
                    <label><input type="radio" name="q5" value="3"> Goes</label>
                </div>
            </div>
            <div class="question">
                <p>6. Fill in the blank: "They _____ to the park yesterday."
                </p>
                <div class="options">
                    <label><input type="radio" name="q6" value="1"> goes</label>
                    <label><input type="radio" name="q6" value="2"> went</label>
                    <label><input type="radio" name="q6" value="3"> going</label>
                </div>
            </div>
            <div class="question">
                <p>7. Which sentence is in the future tense?</p>
                <div class="options">
                    <label><input type="radio" name="q7" value="1"> I am eating dinner.</label>
                    <label><input type="radio" name="q7" value="2"> I will eat dinner.</label>
                    <label><input type="radio" name="q7" value="3"> I ate dinner.</label>
                </div>
            </div>
            <div class="question">
                <p>8. Select the correct spelling:</p>
                <div class="options">
                    <label><input type="radio" name="q8" value="1"> Accomodation</label>
                    <label><input type="radio" name="q8" value="2"> Accommodation</label>
                    <label><input type="radio" name="q8" value="3"> Acommodation</label>
                </div>
            </div>
            <div class="question">
                <p>9. Which word is a verb?</p>
                <div class="options">
                    <label><input type="radio" name="q9" value="1"> Chair</label>
                    <label><input type="radio" name="q9" value="2"> Run</label>
                    <label><input type="radio" name="q9" value="3"> Beautiful</label>
                </div>
            </div>
            <div class="question">
                <p>10. Fill in the blank: "If I _____ rich, I would travel the world."
                </p>
                <div class="options">
                    <label><input type="radio" name="q10" value="1"> am</label>
                    <label><input type="radio" name="q10" value="2"> was</label>
                    <label><input type="radio" name="q10" value="3"> were</label>
                </div>
            </div>
            <div class="question">
                <p>11. Choose the correct sentence:</p>
                <div class="options">
                    <label><input type="radio" name="q11" value="1"> He don’t like apples.</label>
                    <label><input type="radio" name="q11" value="2"> He doesn’t like apples.</label>
                    <label><input type="radio" name="q11" value="3"> He didn’t likes apples.</label>
                </div>
            </div>
            <div class="question">
                <p>12. Which is the opposite of "fast"?</p>
                <div class="options">
                    <label><input type="radio" name="q12" value="1"> Slow</label>
                    <label><input type="radio" name="q12" value="2"> Quick</label>
                    <label><input type="radio" name="q12" value="3"> Rapid</label>
                </div>
            </div>
            <div class="question">
                <p>13. Select the correct article: "I saw _____ elephant in the zoo."
                </p>
                <div class="options">
                    <label><input type="radio" name="q13" value="1"> a</label>
                    <label><input type="radio" name="q13" value="2"> an</label>
                    <label><input type="radio" name="q13" value="3"> the</label>
                </div>
            </div>
            <div class="question">
                <p>14. Fill in the blank: "She has been _____ since morning."
                </p>
                <div class="options">
                    <label><input type="radio" name="q14" value="1"> running</label>
                    <label><input type="radio" name="q14" value="2"> run</label>
                    <label><input type="radio" name="q14" value="3"> runs</label>
                </div>
            </div>
            <div class="question">
                <p>15. Which sentence is grammatically correct?</p>
                <div class="options">
                    <label><input type="radio" name="q15" value="1"> There is two cats.</label>
                    <label><input type="radio" name="q15" value="2"> There are two cats.</label>
                    <label><input type="radio" name="q15" value="3"> There were two cat.</label>
                </div>
            </div>
            <div class="question">
                <p>16. What is the plural of "child"?</p>
                <div class="options">
                    <label><input type="radio" name="q16" value="1"> Childs</label>
                    <label><input type="radio" name="q16" value="2"> Children</label>
                    <label><input type="radio" name="q16" value="3"> Childes</label>
                </div>
            </div>
            <div class="question">
                <p>17. Fill in the blank: "I have never _____ to Paris."
                </p>
                <div class="options">
                    <label><input type="radio" name="q17" value="1"> been</label>
                    <label><input type="radio" name="q17" value="2"> was</label>
                    <label><input type="radio" name="q17" value="3"> be</label>
                </div>
            </div>
            <div class="question">
                <p>18. Which sentence is in the passive voice?</p>
                <div class="options">
                    <label><input type="radio" name="q18" value="1"> The boy kicked the ball.</label>
                    <label><input type="radio" name="q18" value="2"> The ball was kicked by the boy.</label>
                    <label><input type="radio" name="q18" value="3"> The boy is kicking the ball.</label>
                </div>
            </div>
            <div class="question">
                <p>19. Choose the correct comparative form: "This book is _____ than that one."
                </p>
                <div class="options">
                    <label><input type="radio" name="q19" value="1"> interesting</label>
                    <label><input type="radio" name="q19" value="2"> more interesting</label>
                    <label><input type="radio" name="q19" value="3"> most interesting</label>
                </div>
            </div>
            <div class="question">
                <p>20. Fill in the blank: "He _____ his homework before dinner."
                </p>
                <div class="options">
                    <label><input type="radio" name="q20" value="1"> did</label>
                    <label><input type="radio" name="q20" value="2"> does</label>
                    <label><input type="radio" name="q20" value="3"> do</label>
                </div>
            </div>
            <button type="button" class="submit-btn" onclick="calculateLevel()">Submit</button>
        </form>
        <div id="result" class="result"></div>
    </div>
    <script>
        function calculateLevel() {
            const answers = {
                q1: "2",
                q2: "3",
                q3: "2",
                q4: "2",
                q5: "2",
                q6: "2",
                q7: "2",
                q8: "2",
                q9: "2",
                q10: "3",
                q11: "2",
                q12: "1",
                q13: "2",
                q14: "1",
                q15: "2",
                q16: "2",
                q17: "1",
                q18: "2",
                q19: "2",
                q20: "1"
            };

            let score = 0;

            for (const [key, value] of Object.entries(answers)) {
                const selected = document.querySelector(`input[name="${key}"]:checked`);
                if (selected && selected.value === value) {
                    score++;
                }
            }

            let level = "";

            if (score <= 5) {
                level = "A1 (Beginner)";
            } else if (score <= 10) {
                level = "A2 (Elementary)";
            } else if (score <= 15) {
                level = "B1 (Intermediate)";
            } else if (score <= 18) {
                level = "B2 (Upper-Intermediate)";
            } else {
                level = "C1-C2 (Advanced)";
            }

            document.getElementById("result").innerText = `Your level is: ${level}`;
        }
    </script>
</body>
</html>
