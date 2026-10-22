<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coding Club</title>

    <style>
        :root {
            --brand: #2f5bea;
            --light: #eef2ff;
            --dark: #1b2440;
            --gap: 16px;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Georgia, serif;
            background: var(--light);
            color: var(--dark);
            line-height: 1.6;
            padding: var(--gap);
        }

        h1 {
            font-size: 2.2rem;
            letter-spacing: 1px;
        }

        #hero {
            background: var(--brand);
            color: white;
            text-align: center;
            padding: 32px var(--gap);
            border-radius: 10px;
        }

        .card {
            background: white;
            padding: var(--gap);
            margin-top: var(--gap);
            border-radius: 10px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 8px;
        }

        th {
            background: var(--brand);
            color: white;
            text-align: left;
        }

        th, td {
            padding: 8px;
            border-bottom: 1px solid #ccd;
        }

        input {
            padding: 6px;
            margin: 4px 0;
        }

        button {
            background: var(--brand);
            color: white;
            border: 0;
            padding: 10px 18px;
            border-radius: 6px;
            font-size: 1rem;
            cursor: pointer;
        }

        button:hover {
            background: #1b3db5;
        }
    </style>
</head>

<body>

    <div id="hero">
        <h1>Coding Club</h1>
        <p>Learn. Build. Share.</p>
    </div>

    <div class="card">
        <h2>Upcoming Events</h2>

        <table>
            <tr>
                <th>Event</th>
                <th>Date</th>
                <th>Venue</th>
            </tr>

            <tr>
                <td>HTML Workshop</td>
                <td>12 Nov</td>
                <td>Lab 1</td>
            </tr>

            <tr>
                <td>Hackathon</td>
                <td>20 Nov</td>
                <td>Seminar Hall</td>
            </tr>
        </table>
    </div>

    <div class="card">
        <h2>Register</h2>

        <form id="registerForm">
            <p>
                Name:
                <input type="text" id="name" placeholder="Your name" required>
            </p>

            <p>
                Email:
                <input type="email" id="email" placeholder="you@example.com" required>
            </p>

            <button type="submit">
