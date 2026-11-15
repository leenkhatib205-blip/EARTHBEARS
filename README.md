Earth Analogs for the Moon and Mars
An interactive comparison of places on Earth with their counterparts on the lunar South Pole and on Mars. It shows where each analog matches and, just as clearly, where it does not.

Built for the 2026 NASA Space Apps Challenge.

Challenge: Identify Earth Locations that Analog the Permanent Moon Base Locations and Mars
Team: EARTHBEARS
Members: Zeyna ALKHATIB, Yiğit SEZER
Local event: Eskişehir local event
Project page: 

This is a student project. It is not a NASA product and is not endorsed by NASA.
What it does
The project opens on a cover page with two parts.
Part 1: Moon – Lunar South Pole in 3D
A 3D model of the lunar south-pole geologic map next to two polar sites on Earth: Haughton crater (Devon Island, Canada) and McMurdo Sound (Antarctica).
Rotate, zoom and change the light direction.
Click a lunar rock unit in the legend to see the Earth rock it resembles, with a 1–5 similarity rating.
A table for each site rates 17 aspects as similar, different, or a minor or tolerable difference.
A thought experiment: what would have to change for each site to look like the Moon?
Part 2: Mars – 12 Mars–Earth pairs
Twelve Martian regions paired with Earth sites, for example Jezero Crater and Lake Salda (Türkiye), or Valles Marineris and the Grand Canyon.
A Mars map and an Earth map that move together when you pick a pair.
Magnified close-ups side by side.
Cards for each pair: coordinates, landform, how it formed, and temperature.
How to run it
No installation and no build step.

Download or clone this repository.
Open index.html in a modern browser (Chrome, Edge or Firefox).
Choose Moon or Mars on the cover. Use the bar at the top to switch between them or return to the cover.

The 3D library and the page styles are embedded in the files, so the project works without an internet connection. Only the web font on the Mars page needs a connection; without one, the browser uses a system font.
Publish with GitHub Pages
Push the files to a public repository, keeping index.html in the repository root.
In the repository, go to Settings → Pages.
Under Build and deployment, choose Deploy from a branch, select the main branch and the / (root) folder, then save.
After a minute or two the site is available at https://<username>.github.io/<repository>/. Put that link at the top of this file.
Repository structure
index.html        Cover page and viewer that opens the two parts
a_3.html          Mars: 12 Mars–Earth analog pairs
Mars.jpg          Mars base map used by a_3.html
World.jpg         Earth base map used by a_3.html
moon/
  Moon South Pole vs Haughton _ McMurdo · 3D comparison.html
                  Moon: 3D comparison with Haughton and McMurdo
README.md         This file

Keep the files in these positions. index.html loads the other pages by relative path.
Data and sources
Space agency data and missions referenced in the project:

Source
Used for
Mars Global Surveyor, MOLA
Mars elevations, given relative to the MOLA datum
Curiosity, InSight, Viking 2
Surface temperatures and site context on Mars
LCROSS
Water ice in a permanently shadowed crater near the lunar South Pole
Lunar geologic mapping: Spudis et al. (2008), Wilhelms et al. (1979)
Names and ages of the lunar rock units
IM-2 Athena landing site
Marker near the lunar South Pole
[source of Mars.jpg]
Mars base map
[source of World.jpg]
Earth base map
[other sources for elevation and temperature figures]
Mars and Earth site cards


Other material:

Earth site imagery in the Moon page comes from Google Earth (© Google).
The 3D relief in the Moon page is an estimate made for illustration. It is not measured elevation data.
Limits
Similarity ratings are our own judgment. They are not published equivalences.
Earth cannot reproduce lunar or Martian gravity, vacuum, radiation or permanent shadow. The comparison covers landform, geology, temperature, ice and light only.

Credits
three.js r128, MIT License (embedded in the Moon page)
Tailwind CSS, MIT License (generated styles embedded in the Mars page)
Fonts: Inter, JetBrains Mono and Space Grotesk, SIL Open Font License (loaded from Google Fonts by the Mars page)
