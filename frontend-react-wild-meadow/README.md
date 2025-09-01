# mighty-lightning - wild-meadow

## Frontend Module (React + TypeScript + Vite)

### Quick Start

```bash
npm install
npm run dev
```

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production  
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint
- `npm run type-check` - Run TypeScript type checking

### Project Structure

- `src/components/` - Reusable components
- `src/pages/` - Page components
- `src/hooks/` - Custom hooks
- `src/utils/` - Utility functions
- `src/stores/` - State management
- `src/types/` - TypeScript type definitions

### Environment Variables

Copy `.env.example` to `.env.local` and configure your environment variables.

### Technologies Used

- **React 18** - UI library
- **TypeScript** - Type safety
- **Vite** - Fast build tool and dev server
- **ESLint** - Code linting

### Development

The development server runs on http://localhost:5173 with hot module replacement (HMR) enabled.

### Building for Production

```bash
npm run build
```

The build artifacts will be stored in the `dist/` directory.
