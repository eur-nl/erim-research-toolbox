---
title: When Should I Apply for Ethics Approval?
contributors: [Dr. Nami Sunami, Dr. Lizette Guzman-Ramirez]
description: A decision tree to decide when to apply for ethics approval.
---

  <pre class="mermaid">
        graph TB

            personal_data[Collecting or re-using personal data?]
            harm[Potential harm to researcher, staff, or participants?]
            coi[Potential conflict of interest?]
            deception[Using deception, covert, unusual methods or tools?]
            EBL[Using Erasmus Behavioral Lab?]
            non_EU[Research outside the EU?]
            funder_journal[Requested by the funding body or the journal?]
            app_needed[Ethics application needed]
            app_not_needed[No ethics application needed]

            direction TB
            personal_data-- No --> harm
            harm-- No --> coi
            coi-- No --> deception
            deception-- No --> EBL
            EBL-- No --> non_EU
            non_EU -- No --> funder_journal
            funder_journal -- No --> app_not_needed
            personal_data-- Yes --> app_needed
            harm-- Yes --> app_needed
            coi-- Yes --> app_needed
            deception-- Yes --> app_needed
            EBL-- Yes --> app_needed
            non_EU -- Yes --> app_needed
  </pre>

<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
  mermaid.initialize({ startOnLoad: true });
</script>
