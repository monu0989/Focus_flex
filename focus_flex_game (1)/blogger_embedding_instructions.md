# Focus Flex Game - Blogger Embedding Instructions

This document provides step-by-step instructions for embedding the Focus Flex game into your Blogger site. The game is designed to be mobile-responsive and will adapt to different screen sizes.

## Option 1: Direct Embedding via iframe

This is the simplest method to embed the game on your Blogger site.

### Step 1: Access your Blogger Dashboard
1. Log in to your Blogger account
2. Navigate to the blog where you want to embed the game
3. Create a new post or edit an existing one

### Step 2: Switch to HTML View
1. In the post editor, click on the "HTML" button (or "</>" icon) to switch from Compose view to HTML view
2. This allows you to insert custom HTML code

### Step 3: Insert the iframe Code
1. Copy the following code:
```html
<div style="display: flex; justify-content: center; margin: 20px 0;">
  <iframe 
    src="YOUR_DEPLOYED_GAME_URL" 
    width="100%" 
    height="600" 
    style="max-width: 600px; border: none; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);" 
    allowfullscreen>
  </iframe>
</div>
```
2. Replace `YOUR_DEPLOYED_GAME_URL` with the actual URL where the game is hosted
3. Paste the code into the HTML editor where you want the game to appear

### Step 4: Customize (Optional)
- Adjust the `height` value if needed (default is 600px)
- Modify the styling in the `style` attribute to match your blog's design

### Step 5: Publish
1. Click "Update" or "Publish" to save your changes
2. View your post to ensure the game is displaying correctly

## Option 2: Embedding via Google Sites (Alternative Method)

If you prefer not to use direct iframe embedding, you can host the game on Google Sites first.

### Step 1: Create a Google Site
1. Go to [sites.google.com](https://sites.google.com)
2. Create a new site
3. Add an "Embed" element to the page
4. Paste the game's URL or HTML code
5. Publish the Google Site

### Step 2: Embed the Google Site in Blogger
1. In your Blogger post (HTML view), add:
```html
<div style="display: flex; justify-content: center; margin: 20px 0;">
  <iframe 
    src="YOUR_GOOGLE_SITE_URL" 
    width="100%" 
    height="650" 
    style="max-width: 620px; border: none;" 
    allowfullscreen>
  </iframe>
</div>
```
2. Replace `YOUR_GOOGLE_SITE_URL` with your published Google Site URL

## Mobile Optimization Notes

The Focus Flex game is already optimized for mobile devices with:
- Responsive design that adapts to different screen sizes
- Touch-friendly controls
- Appropriate font sizes and button dimensions for mobile interaction

No additional configuration is needed for mobile optimization.

## Troubleshooting

### Game Not Displaying
- Ensure the game URL is correct and accessible
- Check if your blog allows iframe embedding (some Blogger templates may restrict this)
- Try increasing the iframe height if content appears cut off

### Performance Issues
- If the game runs slowly on mobile, ensure your blog doesn't have too many heavy elements loading simultaneously
- Consider placing the game on a dedicated post rather than a sidebar or homepage

### Security Warnings
- If users see security warnings, ensure the game is hosted on a secure (HTTPS) domain
- All modern web hosting services should provide HTTPS by default

## Additional Customization

To introduce the game to your readers, consider adding descriptive text before the iframe:

```html
<p>Challenge your cognitive skills with Focus Flex! This game tests your ability to quickly switch between tasks, maintain focus despite distractions, and react with lightning speed. Track your performance over time with detailed statistics and see how you improve!</p>

<!-- Game iframe code here -->
```

## Need Help?

If you encounter any issues embedding the game, please contact the developer for assistance.
