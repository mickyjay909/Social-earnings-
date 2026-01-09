<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>SOCIAL EARNING HUB</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Earn rewards by completing verified social media tasks.">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Roboto, Arial, sans-serif;
      background: #f0f5f9;
      color: #2d3436;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, #0a8754, #065c37);
      color: #fff;
      padding: 2rem 1rem;
      text-align: center;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    header h1 {
      font-size: 2.2rem;
      margin-bottom: 0.5rem;
      font-weight: 700;
    }

    header p {
      font-size: 1rem;
      opacity: 0.9;
    }

    .container {
      max-width: 950px;
      margin: 2rem auto;
      padding: 0 1rem;
    }

    .hero {
      background: #fff;
      border-radius: 16px;
      padding: 3rem 2rem;
      text-align: center;
      box-shadow: 0 5px 15px rgba(0,0,0,0.05);
      margin-bottom: 2rem;
      position: relative;
      overflow: hidden;
    }

    .hero::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 5px;
      background: linear-gradient(90deg, #0a8754, #27ae60);
    }

    .hero h2 {
      font-size: 1.8rem;
      color: #2d3436;
      margin-bottom: 1.2rem;
    }

    .hero p {
      font-size: 1.1rem;
      color: #636e72;
      max-width: 700px;
      margin: 0 auto 2rem;
    }

    .btn {
      background: linear-gradient(135deg, #0a8754, #065c37);
      color: #fff;
      border: none;
      padding: 12px 28px;
      border-radius: 8px;
      cursor: pointer;
      font-size: 1.1rem;
      font-weight: 500;
      transition: all 0.3s ease;
      text-decoration: none;
      display: inline-block;
    }

    .btn:hover {
      transform: translateY(-2px);
      box-shadow: 0 4px 12px rgba(10, 135, 84, 0.3);
    }

    .btn:disabled {
      background: #b2bec3;
      cursor: not-allowed;
      transform: none;
      box-shadow: none;
    }

    .disclaimer {
      background: #fff3cd;
      color: #856404;
      padding: 1.2rem 1.5rem;
      border-radius: 10px;
      margin-bottom: 2rem;
      font-weight: 500;
      border-left: 5px solid #ffc107;
    }

    .box {
      background: #fff;
      border-radius: 16px;
      padding: 2rem;
      box-shadow: 0 5px 15px rgba(0,0,0,0.05);
      margin-bottom: 2rem;
    }

    .box h3 {
      font-size: 1.4rem;
      color: #0a8754;
      margin-bottom: 1.5rem;
      padding-bottom: 0.5rem;
      border-bottom: 2px solid #f0f5f9;
    }

    .task {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1.2rem;
      margin-bottom: 1rem;
      background: #f8f9fa;
      border-radius: 10px;
      transition: all 0.3s ease;
    }

    .task:hover {
      transform: translateX(3px);
      box-shadow: 0 3px 8px rgba(0,0,0,0.05);
    }

    .task span {
      font-size: 1rem;
      font-weight: 500;
    }

    .task .btn {
      padding: 8px 20px;
      font-size: 0.95rem;
    }

    .wallet-details {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 1.5rem;
      margin-bottom: 1.5rem;
    }

    .wallet-item {
      background: #f8f9fa;
      padding: 1rem;
      border-radius: 10px;
      text-align: center;
    }

    .wallet-item strong {
      color: #0a8754;
      font-size: 1.5rem;
    }

    .legal-info {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
    }

    .legal-info p {
      padding: 0.5rem 0;
      color: #636e72;
    }

    footer {
      background: #2d3436;
      color: #fff;
      padding: 2rem 1rem;
      text-align: center;
      margin-top: 3rem;
    }

    .footer-links {
      margin: 1rem 0;
    }

    .footer-links a {
      color: #a2d9ce;
      text-decoration: none;
      margin: 0 10px;
      font-size: 0.95rem;
    }

    .footer-links a:hover {
      text-decoration: underline;
    }

    footer p {
      font-size: 0.9rem;
      opacity: 0.8;
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 1.8rem;
      }

      .hero h2 {
        font-size: 1.5rem;
      }

      .wallet-details {
        grid-template-columns: 1fr;
      }

      .task {
        flex-direction: column;
        gap: 1rem;
        text-align: center;
      }
    }
  </style>
</head>

<body>

<header>
  <h1>SOCIAL EARNING HUB</h1>
  <p>Registered CAC No. RC 1234567 | TIN: 8901234567</p>
  <p>Earn by completing verified social tasks</p>
</header>

<div class="container">
  <div class="hero">
    <h2>Earn Rewards by Joining Verified Groups & Channels</h2>
    <p>Complete simple social media tasks and get paid – all tasks are linked to legitimate Nigerian businesses!</p>
    <a href="#" class="btn">Register Now (Free)</a>
  </div>

  <div class="disclaimer">
    ⚠️ THIS IS NOT AN INVESTMENT SCHEME. Rewards are paid ONLY for completed, verified tasks. No fees required to join.
  </div>

  <div class="box">
    <h3>How It Works</h3>
    <ol style="padding-left: 1.5rem; color: #636e72;">
      <li style="margin-bottom: 0.8rem;">Register with valid details & complete KYC verification</li>
      <li style="margin-bottom: 0.8rem;">Browse available tasks from approved businesses</li>
      <li style="margin-bottom: 0.8rem;">Complete tasks & submit proof for review</li>
      <li style="margin-bottom: 0.8rem;">Get credited within 24-48 hours after approval</li>
    </ol>
  </div>

  <div class="box">
    <h3>Available Tasks</h3>
    <div class="task">
      <span>Join Telegram Business Group (+₦500)</span>
      <button class="btn" onclick="addBalance(500)">Submit Proof</button>
    </div>
    <div class="task">
      <span>Join WhatsApp Community (+₦500)</span>
      <button class="btn" onclick="addBalance(500)">Submit Proof</button>
    </div>
    <div class="task">
      <span>Follow SME Social Page (+₦500)</span>
      <button class="btn" onclick="addBalance(500)">Submit Proof</button>
    </div>
    <div class="task">
      <span>Share Promotional Post (+₦700)</span>
      <button class="btn" onclick="addBalance(700)">Submit Proof</button>
    </div>
  </div>

  <div class="box">
    <h3>Your Wallet</h3>
    <div class="wallet-details">
      <div class="wallet-item">
        <p>Current Balance</p>
        <strong>₦<span id="balance">0</span></strong>
      </div>
      <div class="wallet-item">
        <p>Minimum Withdrawal</p>
        <strong>₦3,000</strong>
      </div>
    </div>
    <p style="color: #636e72; margin-bottom: 1rem;">Withdrawal Methods: Bank Transfer | Opay | Palmpay</p>
    <button id="withdrawBtn" class="btn" disabled>Request Withdrawal</button>
  </div>

  <div class="box">
    <h3>Business & Regulatory Info</h3>
    <div class="legal-info">
      <p><strong>Registered Name:</strong> Social Earning Hub Nigeria Limited</p>
      <p><strong>CAC No.:</strong> RC 1234567</p>
      <p><strong>TIN:</strong> 8901234567</p>
      <p><strong>Address:</strong> 123 Business Avenue, Ikeja, Lagos</p>
      <p><strong>Compliance:</strong> CBN AML/CFT Guidelines | SEC Consumer Rules</p>
    </div>
  </div>
</div>

<footer>
  <p>Contact: support@socialearninghub.ng | 01-2345678 | 08012345678</p>
  <div class="footer-links">
    <a href="#">Terms of Service</a>
    <a href="#">Privacy Policy</a>
    <a href="#">KYC Requirements</a>
    <a href="#">FAQs</a>
  </div>
  <p>© 2026 Social Earning Hub Nigeria Limited. All Rights Reserved.</p>
</footer>

<script>
  let balance = 0;

  function addBalance(amount) {
    balance += amount;
    document.getElementById("balance").innerText = balance;
    
    if (balance >= 3000) {
      document.getElementById("withdrawBtn").disabled = false;
    }
    
    alert("Task submitted! Your proof will be reviewed within 24hrs – balance will be confirmed shortly.");
  }
</script>

</body>
</html>
