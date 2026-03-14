# Workshop photos

All speaker and organizer cards use **local images** so photos always load on GitHub Pages (no broken or missing images).

## Current placeholders

Each person has an **SVG placeholder** (green circle with initials):

- **Speakers:** `Glenn_Chou.svg`, `Chuchu_Fan.svg`, `Yiannis_Kantaros.svg`, `Hadas_Kress_Gazit.svg`, `Sheila_McIlraith.svg`, `Ahmed_Qureshi.svg`
- **Organizers:** `Neel_Bhatt.svg`, `Jason_Liu.svg`, `Xusheng_Luo.svg`, `Yiwei_Lyu.svg`, `Huy_Tran.svg`, `Lei_Zheng.svg`
- **Advisory:** `Julie_Shah.svg`

## Replacing with real photos

To use a real headshot for someone:

1. Add a photo file in this folder using the **same base name** and a standard extension (e.g. `Glenn_Chou.jpg`, `Chuchu_Fan.png`).
2. In `index.html`, change that person’s `<img>` from the `.svg` to the new file.  
   Example: change `src="images/Glenn_Chou.svg"` to `src="images/Glenn_Chou.jpg"`.

You can also remove the corresponding `.svg` file after updating the HTML if you no longer need the placeholder.
