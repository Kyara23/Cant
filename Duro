<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Crypto Project Evaluation Calculator</title>
<style>
    body {
        font-family: Arial, sans-serif;
        margin: 20px;
    }
    .container {
        max-width: 600px;
        margin: auto;
        padding: 20px;
        border: 1px solid #ccc;
        border-radius: 5px;
        background-color: #f9f9f9;
    }
    .section {
        margin-bottom: 20px;
    }
    label {
        display: block;
        margin-bottom: 5px;
        font-weight: bold;
    }
    input[type="number"] {
        width: 100%;
        padding: 8px;
        margin-bottom: 10px;
        border: 1px solid #ccc;
        border-radius: 5px;
    }
    button {
        padding: 10px 20px;
        background-color: #28a745;
        color: white;
        border: none;
        border-radius: 5px;
        cursor: pointer;
    }
    button:hover {
        background-color: #218838;
    }
    .result {
        margin-top: 20px;
        padding: 20px;
        background-color: #e9ecef;
        border-radius: 5px;
    }
</style>
</head>
<body>

<div class="container">
    <h2>Crypto Project Evaluation Calculator</h2>
    <div class="section">
        <label for="basicInfo">Basic Information (out of 5):</label>
        <input type="number" id="basicInfo" min="0" max="5">
    </div>
    <div class="section">
        <label for="projectOverview">Project Overview (out of 10):</label>
        <input type="number" id="projectOverview" min="0" max="10">
    </div>
    <div class="section">
        <label for="teamPartnerships">Team and Partnerships (out of 15):</label>
        <input type="number" id="teamPartnerships" min="0" max="15">
    </div>
    <div class="section">
        <label for="technology">Technology (out of 20):</label>
        <input type="number" id="technology" min="0" max="20">
    </div>
    <div class="section">
        <label for="tokenomics">Tokenomics (out of 15):</label>
        <input type="number" id="tokenomics" min="0" max="15">
    </div>
    <div class="section">
        <label for="marketPerformance">Market Performance (out of 10):</label>
        <input type="number" id="marketPerformance" min="0" max="10">
    </div>
    <div class="section">
        <label for="communityGovernance">Community and Governance (out of 10):</label>
        <input type="number" id="communityGovernance" min="0" max="10">
    </div>
    <div class="section">
        <label for="risksChallenges">Risks and Challenges (out of 10):</label>
        <input type="number" id="risksChallenges" min="0" max="10">
    </div>
    <div class="section">
        <label for="opportunitiesPotential">Opportunities and Potential (out of 10):</label>
        <input type="number" id="opportunitiesPotential" min="0" max="10">
    </div>
    <div class="section">
        <label for="analystRecommendations">Analyst Recommendations (out of 5):</label>
        <input type="number" id="analystRecommendations" min="0" max="5">
    </div>
    <button onclick="calculateScore()">Calculate</button>
    
    <div class="result" id="result">
        <h3>Result</h3>
        <p id="totalScore">Total Score: </p>
        <p id="allocation">Recommended Portfolio Allocation: </p>
    </div>
</div>

<script>
function calculateScore() {
    let basicInfo = parseInt(document.getElementById('basicInfo').value) || 0;
    let projectOverview = parseInt(document.getElementById('projectOverview').value) || 0;
    let teamPartnerships = parseInt(document.getElementById('teamPartnerships').value) || 0;
    let technology = parseInt(document.getElementById('technology').value) || 0;
    let tokenomics = parseInt(document.getElementById('tokenomics').value) || 0;
    let marketPerformance = parseInt(document.getElementById('marketPerformance').value) || 0;
    let communityGovernance = parseInt(document.getElementById('communityGovernance').value) || 0;
    let risksChallenges = parseInt(document.getElementById('risksChallenges').value) || 0;
    let opportunitiesPotential = parseInt(document.getElementById('opportunitiesPotential').value) || 0;
    let analystRecommendations = parseInt(document.getElementById('analystRecommendations').value) || 0;

    let totalScore = basicInfo + projectOverview + teamPartnerships + technology + tokenomics + marketPerformance + communityGovernance + risksChallenges + opportunitiesPotential + analystRecommendations;
    
    let allocation = '';
    if (totalScore >= 90) {
        allocation = '20-30%';
    } else if (totalScore >= 80) {
        allocation = '15-20%';
    } else if (totalScore >= 70) {
        allocation = '10-15%';
    } else if (totalScore >= 60) {
        allocation = '5-10%';
    } else if (totalScore >= 50) {
        allocation = '0-5%';
    } else {
        allocation = '0%';
    }

    document.getElementById('totalScore').innerText = 'Total Score: ' + totalScore;
    document.getElementById('allocation').innerText = 'Recommended Portfolio Allocation: ' + allocation;
}
</script>

</body>
</html>
