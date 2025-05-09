# Novel Reader

Welcome to **Novel Reader**, an open-source web application for reading and managing novels. This project is built with [TanStack Start](https://tanstack.com/start), providing a modern, fast, and flexible reading experience.

## Features

- 📚 Read and manage your favorite novels
- 🗂️ Organize your library
- 🔖 Bookmark your progress
- 🌙 Light and dark mode
- 🚀 Fast, SPA navigation with TanStack Router
- 🎨 Styled with Tailwind CSS
- 🧪 Tested with Vitest

## Tech Stack

- [TanStack Start](https://tanstack.com/start) (React, TanStack Router)
- [Tailwind CSS](https://tailwindcss.com/)
- [Vitest](https://vitest.dev/) for testing

## Getting Started

To run this application locally:

```bash
pnpm install
pnpm start
```

## Building For Production

To build this application for production:

```bash
pnpm build
```

## Testing

This project uses [Vitest](https://vitest.dev/) for testing. You can run the tests with:

```bash
pnpm test
```

## Styling

This project uses [Tailwind CSS](https://tailwindcss.com/) for styling.

## Routing

This project uses [TanStack Router](https://tanstack.com/router). Routes are managed as files in `src/routes`.

### Adding a Route

To add a new route, create a new file in the `./src/routes` directory. TanStack will automatically generate the content of the route file for you.

### Adding Links

To use SPA navigation, import the `Link` component from `@tanstack/react-router`:

```tsx
import { Link } from "@tanstack/react-router";
```

Then use it in your JSX:

```tsx
<Link to="/about">About</Link>
```

### Using a Layout

The layout is located in `src/routes/__root.tsx`. Anything you add to the root route will appear in all routes. The route content will appear where you use the `<Outlet />` component.

## Data Fetching

You can use TanStack Query or the `loader` functionality in TanStack Router to fetch data for your routes.

## State Management

For state management, you can use [TanStack Store](https://tanstack.com/store/latest) or any other state management solution you prefer.

## License

This project is open source and available under the [MIT License](LICENSE).

---

Happy reading! If you have suggestions or want to contribute, feel free to open an issue or pull request.
