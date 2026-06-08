# Contributing to Awesome Manim 🎬

Thank you for your interest in contributing to Awesome Manim! We're excited to feature your amazing animations.

## How to Contribute

### 1. Fork the Repository
Click the "Fork" button at the top right of the repository page.

### 2. Clone Your Fork
```bash
git clone https://github.com/YOUR-USERNAME/Awesome-Manim.git
cd Awesome-Manim
```

### 3. Create a Feature Branch
```bash
git checkout -b add/your-animation-name
```

### 4. Add Your Animation

#### Option A: Add to Existing Categories
If you have a link to a video, tutorial, or repository, add it to the appropriate file:
- `categories/mathematics.md`
- `categories/computer_science.md`
- `resources/learning.md`
- `resources/plugins.md`

#### Option B: Add a Showcase Creator
If you want to suggest a notable creator, add them to `showcase/creators.md`.

#### Option C: Add Code Examples
Create a new folder in an `examples/` directory (create it if it doesn't exist) with your animation:
```
examples/
├── your_animation_name/
│   ├── your_scene.py          # Your Manim code
│   ├── README.md              # Description and instructions
│   └── thumbnail.png          # Optional preview image
```

### 5. Update Navigation
If you create a new top-level category or resource file, ensure it's linked in the `README.md` navigation table.

### 6. Commit and Push
```bash
git add .
git commit -m "Add: Animation name - Brief description"
git push origin add/your-animation-name
```

### 7. Create a Pull Request
1. Go to your forked repository
2. Click "Compare & pull request"
3. Provide a clear title and description
4. Click "Create pull request"

## Guidelines

### Code Quality
- Ensure your code is well-commented and readable
- Follow Python PEP 8 style guidelines
- Include a `README.md` in your animation folder explaining:
  - What the animation demonstrates
  - How to run it
  - Any dependencies or special requirements

### Documentation
- Provide clear descriptions of your animations
- Include the mathematical or educational concept being demonstrated
- Link to relevant resources or references

### Naming Conventions
- Use clear, descriptive folder names
- Use snake_case for Python file names
- Use descriptive class names following Manim conventions

### Video Links
If you're linking to video content:
- Use high-quality, stable links (preferably YouTube or similar platforms)
- Ensure the content is your own or properly credited
- Include brief timestamps if relevant

## Review Process

1. Your PR will be reviewed by maintainers
2. We may suggest improvements or ask for clarifications
3. Once approved, your contribution will be merged
4. You'll be credited as a contributor

## Code of Conduct

- Be respectful and constructive
- Welcome feedback and suggestions
- Help other contributors
- Share knowledge and resources

## Questions?

- Open an issue for questions or suggestions
- Check existing issues and PRs before creating duplicates
- Join the [Manim Community Discord](https://discord.gg/mMRrZQW) for help

---

Thank you for making Awesome Manim even more awesome! 🌟
