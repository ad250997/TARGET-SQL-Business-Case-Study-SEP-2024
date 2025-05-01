<!DOCTYPE html>
<html>
<body>
    <h1>Target E-commerce Analysis</h1>
    <h2>Overview</h2>
    <p>This case study analyzes Target's Brazilian e-commerce dataset to uncover order trends, geographic preferences, economic impacts, and logistics efficiency. Using SQL, the analysis focuses on:</p>
    <ul>
        <li>Temporal order trends and seasonality</li>
        <li>Geographic distribution of customers and orders</li>
        <li>Pricing, freight costs, and delivery performance</li>
        <li>Payment method adoption and installment preferences</li>
    </ul>

  <h2>Key Insights</h2>

  <h3>1. Order Trends</h3>
  <ul>
      <li><strong>Growth & Seasonality</strong>: Orders peaked in <strong>November 2017</strong> (holiday season) and declined post-2018.</li>
      <li><strong>Time of Day</strong>: Most orders occur in <strong>Afternoon (38%)</strong> and <strong>Night (33%)</strong>.</li>
  </ul>

  <h3>2. Geographic Insights</h3>
  <ul>
      <li><strong>Top States</strong>: São Paulo (SP), Rio de Janeiro (RJ), and Minas Gerais (MG) dominate in total orders and revenue.</li>
      <li><strong>Untapped Potential</strong>: 27% of Brazilian cities (2,199) have no orders, highlighting expansion opportunities.</li>
  </ul>

  <h3>3. Economic Impact</h3>
  <ul>
      <li><strong>Cost Surge</strong>: Orders in Jan-Aug 2018 saw a <strong>137% increase</strong> in total cost compared to 2017.</li>
      <li><strong>Freight Costs</strong>: Remote states like Roraima (RR) have <strong>3x higher average freight costs</strong> than urban hubs.</li>
  </ul>

  <h3>4. Logistics Performance</h3>
  <ul>
      <li><strong>Delivery Times</strong>: Average delivery takes <strong>12 days</strong>; states like Amazonas (AM) face delays due to terrain.</li>
      <li><strong>Efficiency Wins</strong>: Acre (AC) and Rondônia (RO) often deliver <strong>faster than estimated</strong>.</li>
  </ul>

  <h3>5. Payment Behavior</h3>
  <ul>
      <li><strong>Preferred Methods</strong>: Credit cards (58%) and UPI (39%) dominate.</li>
      <li><strong>Installments</strong>: 68% of orders use <strong>single-installment payments</strong> for simplicity.</li>
  </ul>

  <h2>Recommendations</h2>
  <ol>
      <li><strong>Logistics Optimization</strong>:
          <ul>
              <li>Expand distribution centers in remote states (e.g., RR, RO) to reduce freight costs.</li>
              <li>Adopt machine learning for delivery time predictions to improve accuracy.</li>
          </ul>
      </li>
      <li><strong>Regional Growth</strong>:
          <ul>
              <li>Launch localized marketing campaigns in low-order states (e.g., AP, AC) with discounts or influencer partnerships.</li>
              <li>Capitalize on global holidays (e.g., Christmas/Diwali releases).</li>
          </ul>
      </li>
      <li><strong>Payment Strategies</strong>:
          <ul>
              <li>Promote UPI/credit card usage with exclusive offers to boost adoption.</li>
              <li>Simplify installment plans for high-value products.</li>
          </ul>
      </li>
      <li><strong>Operational Improvements</strong>:
          <ul>
              <li>Prioritize same-day delivery in high-demand states (SP, RJ) for premium customers.</li>
              <li>Replicate efficient logistics practices from top-performing states (e.g., AC) to others.</li>
          </ul>
      </li>
  </ol>

  <h2>Methodology</h2>
  <ul>
      <li><strong>Data Exploration</strong>: Analyzed order timestamps, geolocation, and payment data using SQL.</li>
      <li><strong>Aggregation</strong>: Calculated monthly order trends, state-wise metrics, and delivery performance.</li>
      <li><strong>Visualization</strong>: Derived actionable insights through comparative analysis of freight costs, delivery times, and payment patterns.</li>
  </ul>

  <h2>Tools Used</h2>
  <ul>
      <li>SQL (BigQuery)</li>
      <li>Data Aggregation</li>
      <li>Exploratory Analysis</li>
      <li>Dataset can be accessed from here: https://drive.google.com/drive/folders/1FtD_patBlohjtsz1JkUvRNicp4v9j6jj?usp=drive_link</li>
    </ul>
</body>
</html>

