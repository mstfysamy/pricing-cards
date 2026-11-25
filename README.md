<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>subscripe</title>
    <style>*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}

body {
    background-image: linear-gradient(to bottom, #161622 50%, black 50%);
    min-height: 100vh;
    color: rgb(214, 214, 214);
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    background-repeat: no-repeat;
    background-position: center;
    background-attachment: fixed;
    padding: 50px 20px;
}

.head {
    margin: 0px auto 30px auto;
    display: flex;
    flex-direction: column;
    gap: 10px;
}

.head h1 {
    font-size: 38px;
}

.head p {
    font-size: 16px;
}

.container {
    width: 100%;
    max-width: 1000px;
    padding: 0px 20px;
    gap: 24px;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
}

.container .plan1 {
    background-image: linear-gradient(to bottom, #0D0D14, #0D0D14, #0D0D14, #0D0D14, #0D0D14, #7B8CFF);
    border: 2px solid #0D0D14;
}

.container .plan1:hover {
    box-shadow: 0 0 10px #7B8CFF;
    transform: translateY(-5px);
}

.container .plan2 {
    background-image: linear-gradient(to bottom, #0D0D14, #0D0D14, #0D0D14, #0D0D14, #0D0D14, #FF6B7A);
}

.container .plan2:hover {
    box-shadow: 0 0 10px #FF6B7A;
    transform: translateY(-5px);
}

.container .plan3 {
    background-image: linear-gradient(to bottom, #0D0D14, #0D0D14, #0D0D14, #0D0D14, #0D0D14, #FF8A3D);
}

.container .plan3:hover {
    box-shadow: 0 0 10px #FF8A3D;
    transform: translateY(-5px);
}

.container .plan1 h2,
.container .plan1 .price-box p {
    color: #7B8CFF;
}

.container .plan2 h2,
.container .plan2 .price-box p {
    color: #FF6B7A;
}

.container .plan3 h2,
.container .plan3 .price-box p {
    color: #FF8A3D;
}

.container .card {
    padding: 20px;
    display: flex;
    flex-direction: column;
    transition: transform 0.3s,
        box-shadow 0.3s;
    box-shadow: 0 0 10px black;
}

.container .card h2 {
    font-weight: 300;
    letter-spacing: 5px;
    margin-bottom: 7px;
}

.container .card .price-box {
    width: 100%;
    align-items: center;
    justify-content: center;
    display: flex;
    flex-direction: row;
    margin-bottom: 50px;
}

.container .card .price-box p {
    font-size: 37px;
    font-weight: bold;
}

.container .card .price-box .pre {
    display: inline-block;
    width: 45px;
    text-align: start;
    line-height: .8;
    font-weight: bold;
    margin-left: 6px;
}

.container .card ul {
    margin-left: 40px;
    margin-bottom: 80px;
    list-style: none;
    display: flex;
    flex-direction: column;
    gap: 30px;
    justify-content: center;
    text-align: start;
}

.container .card ul li {
    font-size: 16px;
}

.container .card button {
    color: black;
    border: none;
    background-color: #ffffff00;
    font-size: 25px;
    font-weight: bold;
    letter-spacing: 1.5px;
    word-spacing: 5px;
    cursor: pointer;
    margin-top: auto;
}</style>
</head>
<body>
    <header class="head">
        <h1>Simple & Transparent Pricing</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce dignissim pulvinar</p>
    </header>
    <main class="container">
        <article class="plan1 card">
            <h2>BASIC</h2>
            <div class="price-box">
            <p>$19</p>
           <span class="pre"><sup>per month</sup></span>
        </div>
                <ul>
                    <li><span>✔️</span> Sample Text Here</li>
                    <li><span>✔️</span> Your Space Goes Here</li>
                    <li><span>❌</span> Description Space</li>
                    <li><span>❌</span> Sample Text Here</li>
                </ul>
                <button>Buy Now</button>
        </article>
        <article class="plan2 card">
            <h2>STANDARD</h2>
            <div class="price-box">
            <p>$29</p>
           <span class="pre"><sup>per month</sup></span>
           </div>
                <ul>
                    <li><span>✔️</span> Sample Text Here</li>
                    <li><span>✔️</span> Your Space Goes Here</li>
                    <li><span>✔️</span> Description Space</li>
                    <li><span>❌</span> Sample Text Here</li>
                </ul>
                <button>Buy Now</button>
        </article>
        <article class="plan3 card">
            <h2>PREMIUM</h2>
            <div class="price-box">
            <p>$39</p>
           <span class="pre"><sup>per month</sup></span>
           </div>
                <ul>
                    <li><span>✔️</span> Sample Text Here</li>
                    <li><span>✔️</span> Your Space Goes Here</li>
                    <li><span>✔️</span> Description Space</li>
                    <li><span>✔️</span> Sample Text Here</li>
                </ul>
                <button>Buy Now</button>
        </article>
    </main>
</body>
</html>
