# Mind-Blowing Facts Collection

A simple web-based collection of fascinating facts from various scientific and historical domains. The project includes both JSON data files and a styled HTML presentation.

## Project Structure

- `mind_blowing_facts.html` - The HTML presentation of the facts with styled cards
- `mind_blowing_facts.json` - The primary JSON data file containing 20 mind-blowing facts
- `interesting_facts.json` - An alternative collection of interesting facts

## Features

- Responsive card-based layout
- Categorized facts spanning multiple domains including:
  - Space
  - Biology
  - Physics
  - Technology
  - Nature
  - History
  - Science
  and more...
- Clean, readable typography
- Mobile-friendly design

## Usage

### Viewing the HTML Version
Simply open `mind_blowing_facts.html` in any modern web browser to view the styled presentation of facts.

### Using the JSON Data
The JSON files (`mind_blowing_facts.json` and `interesting_facts.json`) can be used as data sources for:
- Web applications
- Educational tools
- API endpoints
- Data analysis

Each fact in the JSON files includes:
- Unique ID
- Category
- Fact content

## Technical Details

### HTML Version
- Uses standard HTML5
- CSS styling included in `<style>` tag
- No external dependencies required

### JSON Structure
```json
{
  "facts": [
    {
      "id": 1,
      "category": "Category Name",
      "fact": "Fact content"
    }
  ]
}
