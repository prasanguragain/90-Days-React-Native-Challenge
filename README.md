# 90-Days-React-Native-Challenge
# React Native Developer Roadmap

This roadmap outlines the key areas and technologies a React Native developer should learn, from fundamental concepts to advanced topics and deployment.

---

## I. Core Concepts

### A. React Native Basics
-   **Creating React Native Modules (iOS)**
-   **Creating React Native Modules (Android)**
-   **Exposing Native Functionality**
-   **Calling Native Modules from JavaScript**
-   **Passing Data between JavaScript and Native**
-   **Threading Considerations**
-   **Debugging Native Modules**

### B. Native APIs
-   **Geolocation**
-   **Camera**
-   **Permissions API**
-   **Push Notifications**
-   **Contacts**
-   **Accelerometer**
-   **Gyroscope**

---

## II. Data Handling

### A. Fetch API
-   **Making API Requests**
-   **Handling Responses**
-   **Error Handling**
-   **Request Headers**
-   **Request Methods (GET, POST, PUT, DELETE)**
-   **Authentication**
-   **CORS**

### B. Async/Storage
-   **Storing Data Locally**
-   **Retrieving Data**
-   **Updating Data**
-   **Deleting Data**
-   **Data Persistence**
-   **Security Considerations**
-   **AsyncStorage Limitations**

### C. Realm
-   **Setting up Realm**
-   **Defining Schemas**
-   **Writing Data**
-   **Reading Data**
-   **Querying Data**
-   **Relationships**
-   **Migrations**

### D. SQLite
-   **SQLite Setup**
-   **Creating Tables**
-   **Inserting Data**
-   **Querying Data**
-   **Updating Data**
-   **Deleting Data**
-   **Transactions**

---

## III. State Management

### A. Component State
-   **Local State Management**
-   `setState()` Method
-   **Handling User Input**
-   **Controlled vs. Uncontrolled Components**
-   **Lifting State Up**
-   **State Management Patterns**
-   **Performance Considerations**

### B. Context API
-   **Creating Contexts**
-   **Providing Values**
-   **Consuming Values**
-   **Updating Context Values**
-   **Context with TypeScript**
-   **Performance Optimization**
-   **When to use Context**

### C. Redux
-   **Actions, Reducers, Store**
-   **Connecting Components to the Store**
-   **Dispatching Actions**
-   **Redux Middleware (Thunk, Saga)**
-   **Redux DevTools**
-   **Redux Best Practices**
-   **Redux with TypeScript**

### D. MobX
-   **Observables and Observers**
-   **Actions and Reactions**
-   **Computed Values**
-   **MobX Provider**
-   **MobX DevTools**
-   **MobX Best Practices**
-   **MobX with TypeScript**

---

## IV. Navigation

### A. React Navigation Library
-   **Stack Navigator**
-   **Tab Navigator**
-   **Drawer Navigator**
-   **Passing Parameters between Screens**
-   **Navigation Lifecycle**
-   **Custom Navigation Options**
-   **Linking and Deep Linking**

### B. Navigation Patterns
-   **Authentication Flow**
-   **Tab-based Navigation**
-   **Drawer-based Navigation**
-   **Nested Navigation**
-   **Conditional Navigation**
-   **Imperative Navigation**
-   **Custom Transitions**

---

## V. Styling and Layout

### A. Flexbox
-   **Flex Direction**
-   **Justify Content**
-   **Align Items**
-   **Align Self**
-   **Flex Grow, Shrink, Basis**
-   **Flexbox Cheatsheet**
-   **Responsive Layouts**

### B. Styling in React Native
-   **Inline Styles**
-   **StyleSheet API**
-   **Styled Components**
-   **Theme Providers**
-   **Platform-Specific Styles**
-   **Dynamic Styling**
-   **Best Practices**

### C. UI Libraries
-   **React Native Paper**
-   **NativeBase**
-   **Material UI**
-   **Ant Design Mobile**
-   **Choosing a UI Library**
-   **Customizing UI Components**
-   **Performance Considerations**

---

## VI. Animations

### A. Animations
-   **Animated API**
-   **LayoutAnimation API**
-   **Reanimated**
-   **Gesture Handling**
-   **Complex Animations**
-   **Performance Considerations**
-   **UI/UX Best Practices**

---

## VII. Internationalization (i18n)

### A. Internationalization
-   **React Native i18n**
-   **Localization**
-   **Handling Different Languages**
-   **Date and Number Formatting**
-   **Right-to-Left Layout**
-   **Testing Localization**

---

## VIII. Accessibility

### A. Accessibility
-   **Accessibility API**
-   **Semantic HTML**
-   **ARIA Roles**
-   **Testing Accessibility**
-   **Screen Readers**
-   **Accessibility Best Practices**

---

## IX. TypeScript

### A. TypeScript Fundamentals
-   **Types and Interfaces**
-   **Classes and Objects**
-   **Generics**
-   **Type Inference**
-   **Decorators**
-   **Modules**
-   **Configuration**

### B. React Native with TypeScript
-   **Typing Components**
-   **Typing Props and State**
-   **Typing Hooks**
-   **Typing Redux**
-   **Typing Context**
-   **Best Practices**
-   **Troubleshooting**

### C. Advanced TypeScript
-   **Utility Types**
-   **Conditional Types**
-   **Mapped Types**
-   **Type Guards**
-   **Declaration Files**
-   **Custom Types**
-   **Integrating with Libraries**

---

## X. Testing

### A. Unit Testing
-   **Jest**
-   **Enzyme**
-   **React Native Testing Library**
-   **Mocking Dependencies**
-   **Writing Test Cases**
-   **Test Coverage**
-   **Test-Driven Development**

### B. End-to-End Testing
-   **Detox**
-   **Appium**
-   **Setting up E2E Tests**
-   **Writing E2E Test Cases**
-   **Running Tests on Devices/Emulators**
-   **Continuous Integration**

### C. UI Testing
-   **Snapshot Testing**
-   **Visual Regression Testing**
-   **Component-Level Testing**
-   **Integration Testing**
-   **Accessibility Testing**
-   **Performance Testing**

---

## XI. Deployment

### A. iOS Deployment
-   **Setting up an Apple Developer Account**
-   **Creating Certificates and Provisioning Profiles**
-   **Building for iOS**
-   **Archiving and Exporting**
-   **TestFlight**
-   **App Store Submission**

### B. Android Deployment
-   **Setting up a Google Play Developer Account**
-   **Generating a Signed APK/AAB**
-   **Building for Android**
-   **Google Play Console**
-   **Internal Testing**
-   **Play Store Submission**

### C. Continuous Integration
-   **Fastlane**
-   **Bitrise**
-   **CircleCI**
-   **Setting up CI/CD Pipelines**
-   **Automated Builds**
-   **Automated Testing**
-   **Automated Deployment**

---

## XII. Performance Optimization

### A. Code Optimization
-   **Memoization (useMemo, useCallback)**
-   **Pure Components**
-   **Virtualized Lists**
-   **Reducing Re-renders**
-   **Optimizing Images**
-   **Code Splitting**

### B. Native Performance
-   **Profiling Tools**
-   **Bridge Performance**
-   **UI Thread Performance**
-   **Memory Management**
-   **Native Driver**
-   **Hermes Engine**

### C. Monitoring
-   **Performance Monitoring Tools**
-   **Crash Reporting**
-   **Analytics**
-   **Identifying Bottlenecks**
-   **Optimizing Network Requests**
-   **Reducing App Size**

---

## XIII. Third-Party Libraries

### A. Third Party Libraries
-   **React Native Camera**
-   **React Native Maps**
-   **React Native Permissions**
-   **React Native Push Notification**
-   **Choosing a Library**
-   **Integrating Libraries**
-   **Troubleshooting**
