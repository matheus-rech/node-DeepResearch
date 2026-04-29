## Configuration
- When customizing `ts-jest` transform in `jest.config.js`, retain the `ts-jest/jest-preset` to avoid losing default configurations like `transformIgnorePatterns`.
- When extending `tsconfig.json` for tests in `tsconfig.test.json`, explicitly override `include` and `exclude` to ensure test directories are included and not filtered out by base exclusions.
