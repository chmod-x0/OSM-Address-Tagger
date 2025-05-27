# Offline Address Tagger

This is a lightweight, browser-based tool for quickly generating OpenStreetMap-compatible address tags. It's useful for mappers who want to assign `addr:*` tags while walking or driving through neighborhoods, especially when editing in iD or Rapid.

## How It Works

1. Enter a **starting house number** and a **number increment**.
2. Fill in the **street**, **city**, **state**, **ZIP code**, and **county**.
3. Click **Start** to generate the first set of address tags.
4. Click **Next** to increment the house number and generate the next set of tags.
5. Use the **Copy** button to copy the current address block to your clipboard.

### Output Format
Each output will be formatted like this:

addr:housenumber=100

addr:street=Example Street

addr:city=Somewhere

addr:state=TX

addr:postcode=12345

addr:county=Example County



---


## Important Usage Notes

- If you're moving on to a **new street**, be sure to:
  1. Update the **Street name** and **Starting number**
  2. Click **Start** again to reset the sequence

- The tool does **not** save previous addresses or history — it's meant to be quick and temporary.

- It works completely **offline** — no server, no tracking, just pure HTML+JS.

---

## Hosting

This tool is hosted via GitHub Pages. You can also clone it and run it locally by just opening `index.html` in your browser.

Enjoy tagging!
