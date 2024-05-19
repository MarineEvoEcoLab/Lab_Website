---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: TRUE

# Order that this section appears on the page.
weight: 40

title: |
    <div style="text-align: left;">
      Selection
    </div> 
subtitle: |
    <div style="display: flex; align-items: center; justify-content: left; text-align: justify;">
      <img src="Selection.png" alt="Sequencer Icon" width="200" style="margin-right: 40px;">
      <div>
        The environmental impacts of an ever-growing human population cross multiple spatial and temporal boundaries, and marine organisms experience all of these stressors simultaneously, increasing the need for research on synergistic effects.  Current research uses controlled, factorial exposure experiments to measure phenotypic and genotypic changes of larvae after exposure to ocean acidification conditions, sewage effluent, and the combination of the two. 
      </div>
    </div>   

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
  - name: Coastal Stressors
    tag: Coastal_Stressors
 
design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '1'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 5

  # For Showcase view, flip alternate rows?
  flip_alt_rows: True
---
