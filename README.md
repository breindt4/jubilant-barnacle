# jubilant-barnacle

<DOCTYPE html>
<html lang="en">
<head>
  <meta charsetcharset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Investor Profile Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      padding: 2rem;
    }
    .form-container {
      background-color: #fff;
      padding: 2rem;
      border-radius: 10px;
      max-width: 600px;
      margin: 0 auto;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    h2 {
      text-align: center;
      margin-bottom: 1.5rem;
    }
    .form-group {
      margin-bottom: 1rem;
    }
    label {
      font-weight: bold;
      display: block;
      margin-bottom: 0.5rem;
    }
    select, input[type="radio"] {
      width: 100%;
      padding: 0.5rem;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      background-color: #007BFF;
      color: #fff;
      border: none;
      padding: 0.75rem 1.5rem;
      border-radius: 5px;
      cursor: pointer;
      width: 100%;
    }
    button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>
  <div class="form-container">
    <h2>Investor Profile Questionnaire</h2>
    <form>
      <div class="form-group">
        <label for="riskTolerance">Risk Tolerance</label>
        <select id="riskTolerance" name="riskTolerance">
          <option value="conservative">Conservative</option>
          <option value="moderate">Moderate</option>
          <option value="aggressive">Aggressive</option>
        </select>
      </div>

      <div class="form-group">
        <label for="taxBracket">Tax Bracket</label>
        <select id="taxBracket" name="taxBracket">
          <option value="low">Low (10–12%)</option>
          <option value="middle">Middle (22–24%)</option>
          <option value="high">High (32–37%)</option>
        </select>
      </div>

      <div class="form-group">
        <label for="timeHorizon">Time Horizon</label>
        <select id="timeHorizon" name="timeHorizon">
          <option value="short">Short-Term (&lt;3 years)</option>
          <option value="mid">Mid-Term (3–10 years)</option>
          <option value="long">Long-Term (10+ years)</option>
        </select>
      </div>

      <div class="form-group">
        <label for="liquidityNeeds">Liquidity Needs</label>
        <select id="liquidityNeeds" name="liquidityNeeds">
          <option value="high">High – need funds anytime</option>
          <option value="moderate">Moderate – occasional access</option>
          <option value="low">Low – funds can be locked long-term</option>
        </select>
      </div>

      <button type="submit">Submit Profile</button>
    </form>
  </div>
</body>
</html>
