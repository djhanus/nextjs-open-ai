
# Next.js OpenAI Project

This is a [Next.js](https://nextjs.org/) project using TypeScript, Tailwind CSS, and pnpm for package management. It is designed for rapid development and easy deployment.

## Getting Started

### Install dependencies

```bash
pnpm install
```

### Run the development server

```bash
pnpm run dev
```

Visit [http://localhost:3000](http://localhost:3000) in your browser.

### Build for production

```bash
pnpm run build
```

### Start the production server

```bash
pnpm start
```



## Project Structure

```
public/    # Static assets (images, icons, etc.)
scripts/   # Utility scripts (e.g., seeding data)
src/       # Application source code
```

- **public/**: Contains static files served directly by Next.js.
- **scripts/**: Utility scripts for development or data management.
- **src/**: Main source code, including pages, components, and styles.

## Build Output

After running `pnpm run build`, the production build output is generated in the `.next/` directory. This includes optimized server and client code, static assets, and other files required for deployment.

## Deploying to Vercel

To deploy this project to Vercel:

1. Push your code to a Git repository (GitHub, GitLab, or Bitbucket).
2. Go to [Vercel](https://vercel.com/) and import your repository.
3. Vercel will automatically detect the Next.js framework and set up the build process:
	- **Build Command:** `pnpm run build`
	- **Install Command:** `pnpm install`
	- **Output Directory:** `.next`
4. Set any required environment variables in the Vercel dashboard (e.g., API keys, secrets).
5. Click "Deploy" to launch your app.

For more details, see the [Vercel Next.js documentation](https://vercel.com/docs/frameworks/nextjs).

## Additional Resources

- [Next.js Documentation](https://nextjs.org/docs)
- [Learn Next.js](https://nextjs.org/learn)
- [Vercel Deployment](https://vercel.com/new)
