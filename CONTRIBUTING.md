# Contribution Guidelines

Thank you for contributing to the CIT 240 Developer Directory! To ensure your Pull Request is accepted and merged smoothly, please follow these exact steps[cite: 1].

## Step-by-Step Instructions

1. **Fork this repository** to your personal GitHub account by clicking the "Fork" button at the top right[cite: 1].
2. **Clone your fork** to your laptop using the terminal:
   `git clone https://github.com/YOUR-USERNAME/cit240-developer-directory.git`
3. **Create a new branch** for your work[cite: 1]. Name it using your last name:
   `git checkout -b add-lastname-profile`
4. **Edit `index.html`**:
   * Open `index.html` in your code editor.
   * Scroll to the bottom where it says `STUDENTS: PASTE YOUR PROFILE CARD DIRECTLY BELOW THIS LINE`.
   * Copy and paste the following HTML template, and replace the placeholder text with your own details:

```html
        <!-- STUDENT CARD: [Your Full Name] -->
        <div class="card">
            <h3>Your Full Name</h3>
            <div class="role">BSIT 3 Student</div>
            <p class="bio">Write a 1-sentence bio about your favorite tech topic or hobby.</p>
            <a href="[https://github.com/YOUR-USERNAME](https://github.com/YOUR-USERNAME)" target="_blank">GitHub Profile</a>
        </div>
