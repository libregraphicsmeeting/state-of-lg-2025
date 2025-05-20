# Processing

Processing is an open-source programming environment designed to make coding accessible for artists, designers, students, and educators. Launched in 2001, it’s  a language, a minimal development environment, and a community that helps people learn how to code through visual and interactive projects. Today, it’s used in classrooms to art studios—for creative exploration, prototyping, and teaching programming fundamentals.

![processing-0-title.png](processing-0-title.png)

- Website: https://processing.org  
- Code: https://github.com/processing/processing4  
- Community: https://discourse.processing.org

---

## Slide 1 - Changelog 2024–2025

![processing-1-changelog.png](processing-1-changelog.png)

Since early 2024, with support from the Processing Foundation, our two-person team resumed active development on Processing. Our main challenge was to reconstruct knowledge of the codebase without a formal handover from the previous maintainer.

We focused on:

- Resuming regular releases and bug fixes
- Preserving as much backward compatibility and stability as possible.
- Making installation and updates more reliable across platforms (.msi for Windows, .dmg for macOS, Snap for Linux)
- Automating build, code signing, and release using GitHub Actions (CI/CD)
- Migrating the build system from Ant to Gradle
- Beginning the transition of the interface to a modern UI framework (Compose Multiplatform)
- Publishing core libraries to Maven Central

---

## Slide 2 - Roadmap

![processing-2-roadmap.png](processing-2-roadmap.png)

- Finalize Compose migration.
- Replace JOGL and AWT.
- Modern CLI
- Support for external editors (VSCode, IntelliJ, etc.)
- Visual refresh: sketchbook explorer, asset manager, examples gallery.
- Improved accessibility, onboarding, and contributor docs.
- Online sharing: sketch URLs, headless runner, experimental WASM builds.
- Explore future web-native PDE.

---

## Slide 3 - pr05 

![processing-3-pr05.png](processing-3-pr05.png)

This year will be the second edition of pr05 (pronounced “pros”), a grant and mentorship initiative by the Processing Foundation. This program supports the professional growth of early to mid-career software developers through hands-on involvement in open-source projects. Applications are open until **May 31, 2025**.

Learn more and apply at: https://processingfoundation.org/grants

---

## Slide 3 - Presence at LGM

- Raphaël de Courville (Processing Community Lead)
- Stef Tervelde (Processing core developer)

---

## Speaker Notes

After the original maintainers stepped down in 2023, Processing faced a period of uncertainty. With a small team and support from the Foundation, we resumed active maintenance, modernized key infrastructure, and began rebuilding the contributor community.

We are welcoming new contributors! The future of Processing depends on growing the community and evolving the platform. We’re excited to share this work with the Libre Graphics community and learn from your experiences.