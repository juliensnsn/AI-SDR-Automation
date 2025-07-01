<h2>🤖 AI SDR Automation</h2>

<h3>📝 Context</h3>
<p>
  The client wanted to automate part of their prospecting process. I implemented an automation flow that qualifies leads via Apollo, contacts them on LinkedIn, adds them to Hubspot, and nurtures them through Kakiyo. When a lead becomes sufficiently warm, a meeting is booked with a sales representative and a notification is sent to the sales team.
</p>

<h3>🛠️ Build</h3>
<ul>
  <li>A list of leads matching the company's target market is generated via Apollo.</li>
  <li>These leads are then created in Hubspot.</li>
  <li>Kakiyo nurtures these leads directly on LinkedIn through conversations. The more interested the lead, the higher their score. All information is synchronized in Hubspot.</li>
  <li>If the lead is warm enough, an AI agent proposes a meeting. If the meeting is booked, the sales representative is notified.</li>
  <li>A monitoring system was implemented to track client conversion after the meeting and to analyze the difference between meetings booked by AI and those booked by an SDR.</li>
</ul>
