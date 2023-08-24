# List of the Selected Technologies &amp; Resources for Full-Stack
## Table of contents
- [Dynamic Forms](#dynamic-forms)
- [Graphics](#graphics)
- [Package Managers](#package-managers)
## Dynamic Forms <a name="dynamic-forms"></a>
- [Paperform](https://paperform.co/): Paperform’s unmatched flexibility empowers you to create dynamic forms, eSignatures, surveys, bookings, payments & more. All in one place. Paperform is your digital Swiss Army Knife.
## Graphics <a name="graphics"></a>
- [Iconfinder](https://www.iconfinder.com/): Millions of graphics for your design projects. Created by independent designers.
- [FontAwesome](https://fontawesome.com/): Font Awesome is the Internet's icon library and toolkit, used by millions of designers, developers, and content creators.
- [Flaticon](https://www.flaticon.com/): Download Free Icons and Stickers for your projects. Images made by and for designers in PNG, SVG, EPS, PSD and CSS formats.
- [Icons8](https://icons8.com/): Features a wide variety of icons in different styles. They offer both free and premium versions, and their collection is regularly updated.
- [Noun Project](https://thenounproject.com/): This platform has a collection of over a million curated icons, created by a global community.
- [Streamline Icons](https://www.streamlinehq.com/): They pride themselves on having the world's largest icon collection. Their icons come in three distinct weights (Light, Regular, and Bold).
- [Material Icons](https://fonts.google.com/icons): These are Google's Material Design icons, they're free and easy to use with good documentation.
- [SVGRepo](https://www.svgrepo.com/): A huge collection of high-quality SVGs, offering free downloads and also a feature to customize the color of the SVGs right on the site.
## Package Managers <a name="package-managers"></a>
- [PNPM](https://pnpm.io/): `pnpm` is a fast, efficient, and deterministic package manager for JavaScript and Node.js. Like `npm` and `yarn`, it manages dependencies for JavaScript projects. However, `pnpm` has some unique features and differences compared to these managers:

1. **Efficient Disk Usage with Symlinks**: The most notable feature of `pnpm` is its use of a content-addressable filesystem to store all of your project's dependencies in a single location. When installing packages, instead of copying them into the `node_modules` folder of your project, `pnpm` uses symlinks to reference them. This results in less disk space usage when multiple projects share the same dependencies.

2. **Strict Dependency Resolution**: Unlike `npm` and `yarn`, `pnpm` won't flatten dependencies by default. This ensures that your project's dependencies are isolated from each other, reducing the risk of accidentally using a package that wasn't explicitly specified in your project's `package.json`.

3. **Performance**: `pnpm` often boasts faster install times compared to `npm` and `yarn`, especially in scenarios where there are many shared dependencies across projects.

4. **Workspace Support**: Like `yarn` workspaces, `pnpm` supports a multi-project workspace setup, which is useful for managing monorepos.

5. **Deterministic**: Just like `yarn`, `pnpm` uses a lockfile (`pnpm-lock.yaml`) to ensure that every install results in the exact same node_modules structure across all environments.

6. **Compatibility**: For the most part, `pnpm` is compatible with the npm ecosystem. However, because of its strict approach to dependency management, some edge cases or assumptions made by certain packages might cause issues. 

7. **Overrides and Hooks**: `pnpm` provides a way to override fields in a package's `package.json` or apply hooks at various stages of the lifecycle.

Despite its benefits, `pnpm` isn't as widely adopted as `npm` or `yarn`. If you're considering using it, you should ensure that your projects and any tooling you rely on are compatible with `pnpm`. 

If you're looking for more efficient disk usage, stricter dependency resolution, and potentially faster installations, then `pnpm` might be worth a try.
