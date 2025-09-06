# Frontend Interview Questions
### Advanced JavaScript Concepts
1. **What is the event loop and how does it work with microtasks and macrotasks?** <br />
    *Explain the JavaScript runtime, call stack, callback queue, and how microtasks (promises) are prioritized over macrotasks (setTimeout, DOM events).*<br />
    TBU

2. **Explain closures and their practical applications**<br />
   *Discuss how closures work, memory implications, and real-world use cases like module patterns, data privacy, and callback functions.*<br />
   TBU

3. **What are the differences between var, let, and const?** <br />
    *Cover scope differences, hoisting behavior, temporal dead zone, and when to use each declaration type.*<br />
    TBU

4. **How does JavaScript handle asynchronous operations?** <br />
    *Discuss callbacks, promises, async/await, error handling strategies, and managing concurrent operations.*<br />
    TBU

5. **Explain prototypal inheritance vs classical inheritance** <br />
    *Cover prototype chain, Object.create(), constructor functions, and ES6 classes.*<br />
    TBU

### TypeScript Specific
1. **What are the benefits of TypeScript and when would you use it?**<br />
    *Discuss static typing, compile-time error detection, better IDE support, and maintainability in large codebases.*<br />
    TBU

2. **Explain advanced TypeScript features like generics, utility types, and conditional types**<br />
    *Cover type safety, code reusability, and complex type manipulations.*<br />
    TBU

### React & Modern Frameworks
#### React Fundamentals
1. **What is the Virtual DOM and how does React's reconciliation work?**<br />
    *Explain the diffing algorithm, React Fiber, and performance optimizations.*<br />
    TBU

2. **Explain React Hooks and their rules**<br />
    *Cover useState, useEffect, useContext, useCallback, useMemo, and the rules of hooks.*<br />
    TBU

3. **What are Higher Order Components (HOC) and when would you use them?**<br />
    *Discuss component composition, code reuse, and alternatives like render props and custom hooks.*<br />
    TBU

4. **Explain controlled vs uncontrolled components**<br />
    *Cover form handling, state management, and performance implications.*<br />
    TBU

#### Advanced React Patterns
1. **How do you create custom hooks and what are their benefits?**<br />
    *Discuss logic extraction, reusability, testing, and composition patterns.*<br />
    TBU

2. **What is React.memo and when should you use it?**<br />
    *Explain performance optimization, shallow comparison, and when memoization helps.*<br />
    TBU

How do you handle state management in large React applications?
Compare Redux, Context API, Zustand, and other state management solutions.

Explain React's Concurrent Features (React 18+)
Discuss Suspense, Concurrent Rendering, automatic batching, and transitions.

Performance Optimization
Web Performance
What are Core Web Vitals and how do you optimize them?
Explain LCP (Largest Contentful Paint), FID (First Input Delay), and CLS (Cumulative Layout Shift).

How do you optimize bundle size and loading performance?
Discuss code splitting, lazy loading, tree shaking, and webpack optimizations.

What strategies do you use for image optimization?
Cover modern formats (WebP, AVIF), responsive images, lazy loading, and CDN usage.

Explain different caching strategies for frontend applications
Discuss HTTP caching, service workers, browser caching, and cache invalidation.

Code Optimization
How do you identify and fix performance bottlenecks?
Explain profiling tools (Chrome DevTools, Lighthouse), performance monitoring, and optimization techniques.

What is lazy loading and how do you implement it?
Cover image lazy loading, component lazy loading, and intersection observer API.

CSS & Styling
Advanced CSS
Explain CSS Grid vs Flexbox and when to use each
Discuss two-dimensional vs one-dimensional layouts and practical use cases.

What are CSS preprocessors and their benefits?
Cover Sass, Less, variables, mixins, nesting, and maintainability improvements.

How do you handle responsive design without media queries?
Discuss CSS Grid, Flexbox, container queries, and intrinsic sizing.

Explain CSS specificity and the cascade
Cover specificity calculation, inheritance, and best practices for maintainable CSS.

Modern CSS Features
What are CSS custom properties (variables) and how do you use them?
Discuss dynamic theming, maintainability, and runtime updates.

Explain CSS-in-JS solutions and their trade-offs
Compare styled-components, emotion, CSS modules, and traditional CSS.

System Design & Architecture
Frontend Architecture
How would you design a scalable component library?
Discuss API design, theming, documentation, versioning, and distribution.

Explain micro-frontend architecture and its benefits/challenges
Cover module federation, independent deployment, team autonomy, and integration challenges.

How do you structure large frontend applications?
Discuss folder structure, module organization, dependency management, and separation of concerns.

What is your approach to state management in complex applications?
Compare different patterns and tools based on application requirements.

Design Patterns
Explain common frontend design patterns
Discuss Observer pattern, Module pattern, Facade pattern, and their JavaScript implementations.

How do you implement error boundaries and error handling?
Cover React error boundaries, global error handling, and user experience considerations.

Build Tools & Development Workflow
Webpack & Build Tools
How does Webpack work and what problems does it solve?
Explain module bundling, dependency graphs, loaders, plugins, and optimization.

What is tree shaking and how does it work?
Discuss dead code elimination, ES modules, and bundle optimization.

How do you optimize build performance?
Cover parallel builds, caching, code splitting, and development vs production configurations.

Development Workflow
Explain your approach to testing frontend applications
Discuss unit testing, integration testing, e2e testing, and testing strategies for React components.

How do you handle CI/CD for frontend projects?
Cover automated testing, build optimization, deployment strategies, and monitoring.

Web Security
Security Fundamentals
What is XSS and how do you prevent it?
Explain Cross-Site Scripting types, sanitization, Content Security Policy, and secure coding practices.

Explain CORS and how it's enforced
Discuss Same-Origin Policy, preflight requests, and proper CORS configuration.

What is Content Security Policy (CSP)?
Cover XSS prevention, resource loading restrictions, and implementation strategies.

Advanced Security
How do you handle authentication and authorization in SPAs?
Discuss JWT tokens, OAuth, secure storage, and session management.

What are common frontend security vulnerabilities?
Cover XSS, CSRF, clickjacking, and mitigation strategies.

Accessibility (A11y)
Accessibility Fundamentals
What is web accessibility and why is it important?
Explain WCAG guidelines, inclusive design, and business benefits.

How do you make websites keyboard accessible?
Discuss focus management, tab order, keyboard navigation, and ARIA attributes.

What are ARIA roles and when do you use them?
Explain semantic markup, screen reader support, and proper ARIA implementation.

Advanced Accessibility
How do you test for accessibility?
Cover automated tools (axe, Lighthouse), manual testing, screen readers, and keyboard testing.

How do you handle accessibility in dynamic content?
Discuss live regions, focus management, and screen reader announcements.

Modern Web Technologies
Progressive Web Apps
What are Progressive Web Apps and their benefits?
Explain service workers, offline functionality, app shell architecture, and native-like features.

How do you implement offline functionality?
Discuss service workers, caching strategies, and data synchronization.

Advanced Browser APIs
Explain the Intersection Observer API and its use cases
Cover lazy loading, infinite scrolling, and performance monitoring.

What are Web Workers and when would you use them?
Discuss background processing, main thread blocking, and performance optimization.

Behavioral & Architectural Questions
Problem Solving
Describe how you would approach optimizing a slow-loading webpage
Demonstrate systematic problem-solving using performance tools and optimization techniques.

How do you handle technical debt in frontend codebases?
Discuss refactoring strategies, gradual improvements, and balancing feature development.

Explain a challenging technical problem you solved and your approach
Demonstrate problem-solving skills, technical depth, and learning ability.

Leadership & Collaboration
How do you mentor junior developers and conduct code reviews?
Discuss knowledge sharing, constructive feedback, and team development.

How do you stay updated with rapidly evolving frontend technologies?
Show continuous learning mindset and ability to evaluate new technologies.

Describe your approach to technical decision-making in a team environment
Demonstrate collaboration, communication, and technical leadership skills.

Coding Challenges
Algorithmic Problems
Implement a debounce function
Test understanding of closures, timing, and practical JavaScript applications.

Build a simple virtual DOM implementation
Assess deep framework knowledge and algorithmic thinking.

Create a custom hook for data fetching with caching
Evaluate React expertise, async handling, and API design skills.

System Design Challenges
Design a real-time chat application frontend
Test architectural thinking, WebSocket handling, and scalability considerations.

Build an autocomplete component
Assess performance optimization, debouncing, accessibility, and user experience.
   