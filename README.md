# vite vue3 typescript storybook

## package.json
```
{
  "name": "vts",
  "private": true,
  "version": "0.0.0",
  "scripts": {
    "dev": "vite",
    "build": "vue-tsc && vite build",
    "preview": "vite preview",
    "storybook": "start-storybook -p 6007",
    "build-storybook": "build-storybook"
  },
  "dependencies": {
    "vue": "^3.2.45"
  },
  "devDependencies": {
    "@babel/core": "^7.20.12",
    "@storybook/addon-actions": "^6.5.16",
    "@storybook/addon-essentials": "^6.5.16",
    "@storybook/addon-interactions": "^6.5.16",
    "@storybook/addon-links": "^6.5.16",
    "@storybook/builder-vite": "^0.2.2",
    "@storybook/testing-library": "^0.0.13",
    "@storybook/vue3": "^6.5.16",
    "@vitejs/plugin-vue": "^4.0.0",
    "babel-loader": "^8.3.0",
    "typescript": "^4.9.3",
    "vite": "^4.1.0",
    "vue-loader": "^16.8.3",
    "vue-tsc": "^1.0.24"
  }
}
```
