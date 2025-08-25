## Release Types: Alpha and Beta

In software development, different release stages help manage stability and features before the final production release.

### 🟠 Alpha Release
- An **early, unstable** version of the software.
- Intended for **internal testing** or early adopters.
- Features may be incomplete and bugs are expected.

### 🔵 Beta Release
- A more stable, but still **not final** version.
- Feature complete, but may have bugs.
- Shared with a wider audience for **testing and feedback**.

---

## Managing Alpha and Beta Releases on GitHub

GitHub supports **pre-releases** to mark versions as Alpha, Beta, or Release Candidates.

### How to create Alpha/Beta releases:

1. **Tag Naming Convention** (Semantic Versioning):
   - Alpha: `v1.0.0-alpha`
   - Beta: `v1.0.0-beta`
   - Stable: `v1.0.0`

2. **Creating Tags via Git CLI:**

   ```bash
   # Create an alpha tag
   git tag -a v1.0.0-alpha -m "Alpha release v1.0.0"
   
   # Create a beta tag
   git tag -a v1.0.0-beta -m "Beta release v1.0.0"
   
   # Push tags to GitHub
   git push origin v1.0.0-alpha
   git push origin v1.0.0-beta```

3. **Creating a Pre-release on GitHub:**

    Go to your repository's Releases page.
    
    Click "Draft a new release".
    
    Select the tag (e.g., v1.0.0-alpha).
    
    Give the release a title (e.g., v1.0.0 Alpha).
    
    Check the box “This is a pre-release”.
    
    Add release notes.
    
    Publish the release.

    **Summary Table**
  
    Release Stage	Tag Example	Pre-release in GitHub?
    
    Alpha	v1.0.0-alpha	Yes (check pre-release)
    
    Beta	v1.0.0-beta	Yes (check pre-release)
    
    Stable	v1.0.0	No


   <img width="865" height="501" alt="image" src="https://github.com/user-attachments/assets/363c30d7-1cc2-47e6-ac29-97f04b2f1e50" />
