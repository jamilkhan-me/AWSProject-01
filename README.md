<!DOCTYPE html>
<!-- saved from url=(0020)http://16.171.43.32/ -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Cloud Infrastructure Portal</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family: 'Segoe UI', sans-serif;
    min-height:100vh;
    overflow:hidden;
    color:white;
    background: linear-gradient(-45deg,#0f172a,#1e3a8a,#3b82f6,#06b6d4);
    background-size:400% 400%;
    animation: gradientBG 15s ease infinite;
}

@keyframes gradientBG{
    0%{background-position:0% 50%;}
    50%{background-position:100% 50%;}
    100%{background-position:0% 50%;}
}

.particles{
    position:absolute;
    width:100%;
    height:100%;
    overflow:hidden;
    z-index:1;
}

.particles span{
    position:absolute;
    display:block;
    width:6px;
    height:6px;
    background:rgba(255,255,255,0.4);
    border-radius:50%;
    animation: float 15s linear infinite;
}

.particles span:nth-child(1){left:10%;animation-delay:0s;}
.particles span:nth-child(2){left:20%;animation-delay:2s;}
.particles span:nth-child(3){left:40%;animation-delay:5s;}
.particles span:nth-child(4){left:60%;animation-delay:1s;}
.particles span:nth-child(5){left:80%;animation-delay:7s;}
.particles span:nth-child(6){left:90%;animation-delay:3s;}

@keyframes float{
    0%{
        transform:translateY(100vh) scale(0);
        opacity:0;
    }
    50%{
        opacity:1;
    }
    100%{
        transform:translateY(-10vh) scale(1);
        opacity:0;
    }
}

.container{
    position:relative;
    z-index:2;
    display:flex;
    justify-content:center;
    align-items:center;
    min-height:100vh;
    padding:20px;
}

.glass{
    width:100%;
    max-width:1100px;
    background:rgba(255,255,255,0.08);
    backdrop-filter:blur(15px);
    border:1px solid rgba(255,255,255,0.15);
    border-radius:24px;
    padding:50px;
    box-shadow:0 25px 50px rgba(0,0,0,0.3);
}

.hero{
    text-align:center;
    margin-bottom:40px;
}

.hero h1{
    font-size:4rem;
    margin-bottom:15px;
    text-shadow:0 0 20px rgba(255,255,255,.5);
}

.hero p{
    font-size:1.2rem;
    color:#dbeafe;
    max-width:700px;
    margin:auto;
    line-height:1.7;
}

.status{
    margin-top:25px;
    display:inline-block;
    padding:12px 28px;
    border-radius:30px;
    background:rgba(16,185,129,.2);
    border:1px solid rgba(16,185,129,.4);
    color:#a7f3d0;
    font-weight:bold;
}

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
}

.card{
    background:rgba(255,255,255,0.08);
    border:1px solid rgba(255,255,255,0.1);
    border-radius:18px;
    padding:25px;
    transition:.3s;
}

.card:hover{
    transform:translateY(-8px);
    background:rgba(255,255,255,0.12);
}

.card h3{
    margin-bottom:10px;
    font-size:1.2rem;
}

.card p{
    color:#dbeafe;
    line-height:1.6;
}

.footer{
    text-align:center;
    margin-top:40px;
    color:#cbd5e1;
}

.footer strong{
    color:white;
}
</style>
</head>

<body>

<div class="particles">
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
</div>

<div class="container">
    <div class="glass">

        <div class="hero">
<h3>Project One</h3>
<br>
            <h1>☁️ Cloud Infrastructure</h1>

            <p>
                Welcome to my cloud-hosted environment. This server is running
                securely and efficiently, powered by modern cloud technologies,
                automation, and scalable infrastructure.
            </p>

            <div class="status">
                ● SYSTEM STATUS: OPERATIONAL
            </div>
        </div>

        <div class="grid">

            <div class="card">
                <h3>🚀 Deployment</h3>
                <p>
                    Continuous deployment pipelines deliver applications
                    quickly and reliably.
                </p>
            </div>

            <div class="card">
                <h3>🔒 Security</h3>
                <p>
                    Protected by security groups, encryption,
                    and cloud best practices.
                </p>
            </div>

            <div class="card">
                <h3>⚡ Performance</h3>
                <p>
                    Optimized infrastructure designed for speed,
                    resilience, and scalability.
                </p>
            </div>

            <div class="card">
                <h3>☁️ AWS Ready</h3>
                <p>
                    Built with cloud-native architecture using
                    AWS services and automation.
                </p>
            </div>

        </div>

        <div class="footer">
            <p>
                Built with ❤️  by <strong>Jamil Khan</strong>
            </p>
           
        </div>

    </div>
</div>




</body></html>
