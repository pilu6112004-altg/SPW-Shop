<!DOCTYPE html>
<html lang="my">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SPW Shop - IMO Diamond</title>

  <style>
    * {
      box-sizing: border-box;
      font-family: Arial, "Myanmar Text", sans-serif;
    }

    body {
      margin: 0;
      background: #f3f6fb;
      color: #222;
    }

    .header {
      background: linear-gradient(135deg, #6a5cff, #3b82f6);
      color: white;
      padding: 28px 18px;
      text-align: center;
    }

    .header h1 {
      margin: 0;
      font-size: 30px;
    }

    .header p {
      margin: 8px 0 0;
      opacity: .9;
    }

    .container {
      max-width: 600px;
      margin: 20px auto;
      padding: 0 15px 40px;
    }

    .card {
      background: white;
      border-radius: 16px;
      padding: 20px;
      margin-bottom: 18px;
      box-shadow: 0 5px 20px rgba(0,0,0,.08);
    }

    h2 {
      margin-top: 0;
      font-size: 20px;
    }

    .price-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 10px;
    }

    .price {
      border: 2px solid #e5e7eb;
      border-radius: 12px;
      padding: 14px;
      cursor: pointer;
      background: white;
      transition: .2s;
    }

    .price:hover {
      border-color: #5b5bf7;
    }

    .price input {
      margin-right: 7px;
    }

    .diamond {
      font-weight: bold;
    }

    .ks {
      color: #555;
      margin-top: 4px;
      font-size: 14px;
    }

    label {
      display: block;
      margin-bottom: 7px;
      font-weight: bold;
    }

    input[type="text"],
    input[type="file"] {
      width: 100%;
      padding: 13px;
      border: 1px solid #d6d9df;
      border-radius: 10px;
      margin-bottom: 15px;
      font-size: 16px;
    }

    .payment {
      background: #fff7df;
      border: 1px solid #f3d36b;
      border-radius: 12px;
      padding: 15px;
      margin-bottom: 15px;
    }

    .payment strong {
      color: #c88700;
      font-size: 18px;
    }

    button {
      width: 100%;
      border: 0;
      border-radius: 12px;
      padding: 15px;
      background: linear-gradient(135deg, #6a5cff, #3b82f6);
      color: white;
      font-size: 17px;
      font-weight: bold;
      cursor: pointer;
    }

    .notice {
      background: #eef6ff;
      border-radius: 12px;
      padding: 14px;
      margin-top: 15px;
      line-height: 1.7;
      font-size: 14px;
    }

    .success {
      display: none;
      background: #e9fff1;
      border: 1px solid #64c889;
      color: #126b37;
      padding: 18px;
      border-radius: 12px;
      margin-top: 18px;
      line-height: 1.7;
    }

    .footer {
      text-align: center;
      color: #777;
      font-size: 13px;
      margin-top: 25px;
    }

    @media (max-width: 420px) {
      .price-grid {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>

<body>

  <div class="header">
    <h1>💎 SPW Shop</h1>
    <p>IMO Diamond Top Up</p>
  </div>

  <div class="container">

    <div class="card">
      <h2>💎 Diamond Package ရွေးပါ</h2>

      <div class="price-grid">

        <label class="price">
          <input type="radio" name="package" value="10 Diamond - 1,000 KS">
          <span class="diamond">10 Diamond</span>
          <div class="ks">1,000 KS</div>
        </label>

        <label class="price">
          <input type="radio" name="package" value="50 Diamond - 4,700 KS">
          <span class="diamond">50 Diamond</span>
          <div class="ks">4,700 KS</div>
        </label>

        <label class="price">
          <input type="radio" name="package" value="100 Diamond - 9,000 KS">
          <span class="diamond">100 Diamond</span>
          <div class="ks">9,000 KS</div>
        </label>

        <label class="price">
          <input type="radio" name="package" value="200 Diamond - 18,000 KS">
          <span class="diamond">200 Diamond</span>
          <div class="ks">18,000 KS</div>
        </label>

        <label class="price">
          <input type="radio" name="package" value="300 Diamond - 27,000 KS">
          <span class="diamond">300 Diamond</span>
          <div class="ks">27,000 KS</div>
        </label>

        <label class="price">
          <input type="radio" name="package" value="400 Diamond - 35,500 KS">
          <span class="diamond">400 Diamond</span>
          <div class="ks">35,500 KS</div>
        </label>

        <label class="price">
          <input type="radio" name="package" value="500 Diamond - 44,000 KS">
          <span class="diamond">500 Diamond</span>
          <div class="ks">44,000 KS</div>
        </label>

        <label class="price">
          <input type="radio" name="package" value="600 Diamond - 53,500 KS">
          <span class="diamond">600 Diamond</span>
          <div class="ks">53,500 KS</div>
        </label>

        <label class="price">
          <input type="radio" name="package" value="700 Diamond - 61,500 KS">
          <span class="diamond">700 Diamond</span>
          <div class="ks">61,500 KS</div>
        </label>

        <label class="price">
          <input type="radio" name="package" value="800 Diamond - 69,500 KS">
          <span class="diamond">800 Diamond</span>
          <div class="ks">69,500 KS</div>
        </label>

        <label class="price">
          <input type="radio" name="package" value="900 Diamond - 78,000 KS">
          <span class="diamond">900 Diamond</span>
          <div class="ks">78,000 KS</div>
        </label>

        <label class="price">
          <input type="radio" name="package" value="1000 Diamond - 87,000 KS">
          <span class="diamond">1000 Diamond</span>
          <div class="ks">87,000 KS</div>
        </label>

      </div>
    </div>

    <div class="card">
      <h2>👤 IMO Account</h2>

      <label for="imoid">IMO ID ထည့်ပါ</label>
      <input
        type="text"
        id="imoid"
        placeholder="ဥပမာ - 123456789"
      >

      <div class="payment">
        💰 <b>ငွေရှင်းရန်</b><br><br>
        KBZ Pay<br>
        <strong>09890421937</strong>
      </div>

      <label for="receipt">🧾 ငွေလွှဲပြေစာ ဓာတ်ပုံ</label>
      <input type="file" id="receipt" accept="image/*">

      <div class="notice">
        ⚠️ ငွေလွှဲပြီးနောက် ပြေစာကို သေချာတင်ပေးပါ။<br>
        Order တင်ပြီးပါက <b>၁၅ မိနစ်အတွင်း</b> Diamond ရောက်ရှိပါမည်။
      </div>
    </div>

    <div class="card">
      <button onclick="submitOrder()">📤 Order တင်မည်</button>

      <div class="success" id="success">
        ✅ Order တင်ပြီးပါပြီ။<br><br>
        သင့် Order ကို စစ်ဆေးပြီး
        <b>၁၅ မိနစ်အတွင်း</b> Diamond ဖြည့်ပေးပါမည်။
      </div>
    </div>

    <div class="footer">
      © 2026 SPW Shop • IMO Diamond Top Up
    </div>

  </div>

  <script>
    function submitOrder() {

      const imo = document.getElementById("imoid").value.trim();
      const receipt = document.getElementById("receipt").files.length;
      const selected = document.querySelector(
        'input[name="package"]:checked'
      );

      if (!selected) {
        alert("💎 Diamond Package ကို ရွေးပေးပါ။");
        return;
      }

      if (!imo) {
        alert("👤 IMO ID ထည့်ပေးပါ။");
        return;
      }

      if (!receipt) {
        alert("🧾 ငွေလွှဲပြေစာ ဓာတ်ပုံ တင်ပေးပါ။");
        return;
      }

      document.getElementById("success").style.display = "block";

      window.scrollTo({
        top: document.body.scrollHeight,
        behavior: "smooth"
      });
    }
  </script>

</body>
</html>
