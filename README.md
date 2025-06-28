# Customer_clasification_based_on_clustering-

<h2>Project Title: Predicting Gym-Member Churn &amp; Segmenting Customer Profiles</h2>

<p>
  This project predicts whether a gym customer will renew their membership for the next month by analysing membership details,
  personal attributes, and historical facility-usage data.
</p>

<h3>Workflow Summary</h3>
<ol>
  <li>
    <strong>Data ingestion &amp; preparation</strong><br />
    Imported the raw membership dataset, removed duplicates/missing values, and engineered model-ready features.
  </li>
  <li>
    <strong>Exploratory analysis</strong><br />
    Inspected feature distributions, correlations, and target-class balance (≈&nbsp;25&nbsp;% churners).
  </li>
  <li>
    <strong>Supervised modelling</strong><br />
    Trained and compared several models—linear regression and random-forest variants—both with and without highly correlated
    features. The full-feature random-forest model delivered the best predictive accuracy and feature-importance insight.
  </li>
  <li>
    <strong>Unsupervised clustering (K-Means)</strong><br />
    Grouped users into <strong>five clusters</strong>. Clusters <strong>0</strong> and <strong>2</strong> exhibited the highest
    cancellation rates. Key differentiators were lower engagement with membership benefits (classes, friend/partner promos) in
    cluster&nbsp;2, and location-driven restrictions in cluster&nbsp;0.
  </li>
  <li>
    <strong>Business recommendations</strong>
    <ul>
      <li>Improve communication about available perks.</li>
      <li>Investigate access barriers to benefits.</li>
      <li>Promote longer-term contracts to stabilise revenue.</li>
      <li>Tailor retention campaigns to younger members (cluster&nbsp;2) and address location constraints for cluster&nbsp;0.</li>
    </ul>
  </li>
</ol>

<p>
  By combining predictive modelling with customer segmentation, the project gives management a data-driven playbook for
  reducing churn and boosting member engagement.
</p>
