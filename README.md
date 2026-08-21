<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Profile - Laptop Store</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: #f3f4f6;
            color: #222;
        }

        /* Navbar */
        header {
            background: #111827;
            color: white;
            padding: 18px 7%;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
        }

        nav a:hover {
            color: #38bdf8;
        }

        /* Profile */
        .profile-container {
            max-width: 900px;
            margin: 50px auto;
            padding: 0 20px;
        }

        .profile-card {
            background: white;
            border-radius: 15px;
            padding: 35px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.08);
        }

        .profile-header {
            text-align: center;
            border-bottom: 1px solid #ddd;
            padding-bottom: 25px;
            margin-bottom: 25px;
        }

        .profile-picture {
            width: 110px;
            height: 110px;
            background: #2563eb;
            color: white;
            border-radius: 50%;
            margin: auto;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 50px;
        }

        .profile-header h1 {
            margin-top: 15px;
        }

        .profile-header p {
            color: #666;
            margin-top: 7px;
        }

        /* Information */
        .info {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
        }

        .info-box {
            background: #f9fafb;
            padding: 18px;
            border-radius: 10px;
        }

        .info-box strong {
            display: block;
            color: #555;
            margin-bottom: 7px;
        }

        .info-box span {
            font-size: 17px;
        }

        /* Buttons */
        .buttons {
            margin-top: 30px;
            display: flex;
            gap: 15px;
        }

        .btn {
            padding: 13px 25px;
            border: none;
            border-radius: 7px;
            background: #2563eb;
            color: white;
            text-decoration: none;
            cursor: pointer;
            font-weight: bold;
        }

        .btn:hover {
            background: #1d4ed8;
        }

        .logout {
            background: #dc2626;
        }

        .logout:hover {
            background: #b91c1c;
        }

        /* Footer */
        footer {
            background: #111827;
            color: white;
            text-align: center;
            padding: 25px;
            margin-top: 50px;
        }

        /* Mobile */
        @media (max-width: 600px) {
            header {
                flex-direction: column;
                gap: 15px;
            }

            nav a {
                margin: 0 7px;
            }

            .info {
                grid-template-columns: 1fr;
            }

            .buttons {
                flex-direction: column;
            }

            .btn {
                text-align: center;
            }
        }
    </style>
</head>

<body>

    <!-- Navbar -->
    <header>
        <div class="logo">💻 Laptop Store</div>

        <nav>
            <a href="index.html">Home</a>
            <a href="categories.html">Categories</a>
            <a href="profile.html">Profile</a>
            <a href="#">Cart 🛒</a>
        </nav>
    </header>


    <!-- Profile Section -->
    <div class="profile-container">

        <div class="profile-card">

            <div class="profile-header">

                <div class="profile-picture">
                    👤
                </div>

                <h1>Abhay Patil</h1>
                <p>Customer Account</p>

            </div>


            <!-- User Information -->
            <div class="info">

                <div class="info-box">
                    <strong>Full Name</strong>
                    <span>Abhay Patil</span>
                </div>

                <div class="info-box">
                    <strong>Email</strong>
                    <span>abhay@example.com</span>
                </div>

                <div class="info-box">
                    <strong>Phone Number</strong>
                    <span>+91 98765 43210</span>
                </div>

                <div class="info-box">
                    <strong>Address</strong>
                    <span>Maharashtra, India</span>
                </div>

                <div class="info-box">
                    <strong>Total Orders</strong>
                    <span>12 Orders</span>
                </div>

                <div class="info-box">
                    <strong>Member Since</strong>
                    <span>2026</span>
                </div>

            </div>


            <!-- Buttons -->
            <div class="buttons">

                <a href="#" class="btn">
                    ✏️ Edit Profile
                </a>

                <a href="#" class="btn">
                    📦 My Orders
                </a>

                <a href="#" class="btn logout">
                    🚪 Logout
                </a>

            </div>

        </div>

    </div>


    <!-- Footer -->
    <footer>
        <p>© 2026 Laptop Store. All Rights Reserved.</p>
    </footer>

</body>
</html>
