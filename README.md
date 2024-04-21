# GIDS-Banking-Innovation

## Introduction (Ethos)
 - Introduction about me, Wells Fargo, LOB/Business Unit
 - List of initiatives/themes and corresponding achievements in Wells Fargo

## Setting the Scene
### Context Setting
- Context on Commercial Payments and Treasury
- Explanation of how stable and robust applications are built
- **Case Study**: Bank Operations & Common issues/pain points (Pathos - Engaging)
- Explaining Agenda of Session:
  - How apps are built stable and reliable with industry patterns    
  - Exlain the business requirement of scaling, How to test or measure to quantify (NFR Techniques)     
  - Operator app
  - Techniques to improve efficiency using technology
[Detailed Information](Slides-Walkthrough-Narration.md)

## Action & Responsibility
### (Logos) : Factual Information
- Steps taken to enrich operator experience
- [Include stats, evidence from Gartner or similar consulting firm from Industry]

## Deck Walk-through
- Sequence of slides to walk through with slides in appendix
- Lessons Learnt & Observations (with remediation plan)

## ML and GenAI spplicability in Tresury Banking
- Automated Psyment Repair
- ML based STP rules
- Bot for Operator to ease their repair process by automasting Standard Operasting Procedures from vasrious sources 
- AI in check scanning & proecssing [Check scanning & processing](/references/check-processing-ai)
- AI 

## References
[duties of teller](references/teller.md)


<details>
  <summary>Select an option</summary>
  <p>

    <select id="options" onchange="showSection()">
      <option value="">Select an option</option>
      <option value="section1">Section 1</option>
      <option value="section2">Section 2</option>
      <option value="section3">Section 3</option>
    </select>

    <div id="section1" style="display:none;">
      This is Section 1 content.
    </div>

    <div id="section2" style="display:none;">
      This is Section 2 content.
    </div>

    <div id="section3" style="display:none;">
      This is Section 3 content.
    </div>

    <script>
      function showSection() {
        var selectBox = document.getElementById("options");
        var selectedValue = selectBox.options[selectBox.selectedIndex].value;
        var sections = document.querySelectorAll("[id^='section']");
        
        sections.forEach(function(section) {
          section.style.display = "none";
        });

        if (selectedValue !== "") {
          document.getElementById(selectedValue).style.display = "block";
        }
      }
    </script>

  </p>
</details>
## Search and Redirect Example

<input type="text" id="searchInput" placeholder="Search for content.." onkeyup="searchAndRedirect(event)">
<button onclick="clearSearch()">Clear</button>

<div id="searchResults">
  <!-- Search results will be displayed here -->
</div>

<details> <p>
<script>
function searchAndRedirect(event) {
  if (event.keyCode === 13) { // Check if Enter key is pressed
    var searchQuery = document.getElementById("searchInput").value.toLowerCase();
    // Perform search and redirection logic here
    // Example: Assume child pages are stored in a directory named 'pages'
    var pageUrl = 'pages/' + searchQuery + '.md'; // Construct URL based on search query
    window.location.href = pageUrl; // Redirect to the page
  }
}

function clearSearch() {
  document.getElementById("searchInput").value = "";
  document.getElementById("searchResults").innerHTML = ""; // Clear search results
}
</script>
</p>
</details>