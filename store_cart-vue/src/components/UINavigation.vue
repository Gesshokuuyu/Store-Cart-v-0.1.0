<template>
<div class="sidebar">
        <div class="logo"> <span class="icon">▶</span> <span class="text">shape<span class="highlight">4</span></span> </div>
        <nav>
            <p class="section-title">MAIN APP</p>
            <ul>
                <li><a href="#"><span class="icon">🏠</span> Home</a></li>
                <li class="active"><a href="#"><span class="icon">📁</span> Projects</a></li>
                <li><a href="#"><span class="icon">💬</span> Conversations</a></li>
                <li><a href="#"><span class="icon">📊</span> Analytics</a></li>
            </ul>
            <p class="section-title">OTHERS</p>
            <ul>
                <li><a href="#"><span class="icon">📅</span> Events <span class="badge">2</span></a></li>
            </ul>
        </nav>
        <div class="footer">
            <a href="#">Setting</a> | <a href="#">Help</a> | <a href="#">Policy</a>
        </div>
    </div>
</template>

<script>

</script>

<style scoped>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #2e1f3a;
        }
        .sidebar {
            position: fixed;
            top: 0;
            left: 0;
            width: 250px;
            height: 100vh;
            background: linear-gradient(180deg, #4b1e60, #2e1f3a);
            color: white;
            padding: 20px;
            box-shadow: 2px 0 5px rgba(0, 0, 0, 0.2);
        }
        .logo {
            font-size: 20px;
            font-weight: bold;
            display: flex;
            align-items: center;
        }
        .highlight {
            color: #b47dfa;
        }
        .section-title {
            font-size: 12px;
            margin: 15px 0 5px;
            color: #ccc;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        li {
            padding: 10px;
            border-radius: 5px;
            cursor: pointer;
            display: flex;
            align-items: center;
            transition: background 0.3s;
        }
        li a {
            text-decoration: none;
            color: white;
            display: flex;
            align-items: center;
            width: 100%;
        }
        li .icon {
            margin-right: 10px;
        }
        li:hover, .active {
            background: #b47dfa;
        }
        .badge {
            background: red;
            color: white;
            padding: 2px 6px;
            border-radius: 50%;
            font-size: 12px;
            margin-left: auto;
        }
        .footer {
            position: absolute;
            bottom: 20px;
            font-size: 12px;
            width: 200px;
            text-align: center;
        }
        .footer a {
            color: #b47dfa;
            text-decoration: none;
        }
</style>