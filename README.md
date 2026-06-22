# Day 19 Word Practice

An English vocabulary practice page for children. It is a static website and can be deployed as-is.

## Files

- `index.html` - the whole app

## Quick Public Deploy

### Option 1: Netlify Drop

1. Open https://app.netlify.com/drop
2. Drag the whole `New project` folder into the page.
3. Netlify will create a public website URL.

This is the easiest method because it does not require code tools.

### Option 2: GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` to the repository root.
3. Go to repository `Settings` -> `Pages`.
4. Choose `Deploy from a branch`.
5. Select the `main` branch and `/root`.
6. Save, then wait for GitHub to create the public URL.

## Data Note

User ID scores, progress, and wrong-book records are stored in the browser with `localStorage`.
This means each device/browser keeps its own records. To sync records across devices, add a cloud database such as Supabase or Firebase.
