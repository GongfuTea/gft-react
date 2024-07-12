# @gft-react/shadcn-ui


This project serves as a convenient wrapper around the `shadcn-ui` components, aiming to streamline their integration and usage within your projects. It's designed to bring together the powerful UI components from `shadcn-ui` under a unified and simplified interface.

## Prerequisites

Before you begin using this wrapper, it's essential to initialize `shadcn-ui` following its standard initialization procedures. This ensures that all underlying functionalities and components from `shadcn-ui` are correctly set up and ready to be utilized through this wrapper.

## TailwindCSS Configuration

To fully leverage the `shadcn-ui` components within your project, you must also configure TailwindCSS to include the files from the `shadcn-ui` package. Specifically, your TailwindCSS configuration should be extended to process the TypeScript and TSX files located at:

```

  content: [
    './pages/**/*.{ts,tsx}',
    './components/**/*.{ts,tsx}',
    './app/**/*.{ts,tsx}',
    './src/**/*.{ts,tsx}',
    './node_modules/@gft-react/shadcn-ui/**/*.{ts,tsx,js}'
  ],

```


This step is crucial as it allows TailwindCSS to apply its utility-first styling capabilities directly to the `shadcn-ui` components, ensuring a seamless integration and consistent look and feel across your application.

## Getting Started

1. **Initialize `shadcn-ui`:** Follow the initialization guide provided by `shadcn-ui` to set up the library in your project.
2. **Configure TailwindCSS:** Modify your `tailwind.config.js` file to include the `shadcn-ui` components as described above.
3. **Use `shadcn-ui` Components:** With the initialization and configuration complete, you can now use the `shadcn-ui` components within your project through this wrapper.

## Conclusion

This wrapper aims to simplify the usage of `shadcn-ui` components by providing a unified interface and ensuring that the necessary configurations, such as TailwindCSS integration, are highlighted and easy to implement. By following the steps outlined above, you can enhance your project with the robust and versatile components from `shadcn-ui`, all while maintaining a consistent and customizable design system.