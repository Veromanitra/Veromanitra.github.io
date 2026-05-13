---
title: "Research"
toc: true
---

<script>
function hide_buttons(button, abstract) {
  var x = document.getElementById(abstract);
  if (x.style.display === "none") {
    x.style.display = "block";
    button.classList.add('toggled');
  } else {
    x.style.display = "none";
    button.classList.remove('toggled');
  }
}
</script>

<style>

.button_link {
  background-color: transparent; /* blue background */
  color: currentColor; /* white text */
  border: transparent; /* remove default border */
  border-radius: 5px; /* rounded corners */
  padding: 10px 20px; /* add some padding */
  cursor: pointer; /* change cursor on hover */
  transition: background-color 0.3s ease; /* smooth transition on hover */
  display: inline-flex;
  align-items: center; 
  font-weight: bold;
}

.button_link:hover {
  background-color: transparent;
}

.button_link::before {
  content: "";
  display: inline-block;
  width: 0;
  height: 0;
  border-style: solid;
  border-width: 5px 0 5px 10px;
  border-color: transparent transparent transparent #000;
  margin-right: 10px;
  transition: transform 0.2s;
}

.button_link.toggled::before {
  transform: rotate(90deg);
}

h4 {
  margin-top: 2rem; 
  margin-bottom: 0.5rem;
}
</style>

</style>

On-going works
------
 

Publications
------




Other publications
------
