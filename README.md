### **JavaScript:**

1. **JavaScript এ `let`, `var`, এবং `const` এর মধ্যে পার্থক্য কী?**
   - `var` function-scoped, যেখানে `let` এবং `const` block-scoped। `const` এর মান পুনরায় নির্ধারণ করা যায় না।

2. **JavaScript এ `==` এবং `===` এর মধ্যে পার্থক্য কী?**
   - `==` (loose equality) type conversion করে, কিন্তু `===` (strict equality) type conversion ছাড়াই তুলনা করে।

3. **JavaScript এর Closures কী?**
   - Closure হল একটি function, যা তার lexical scope এর মধ্যে থাকা variables access করতে পারে, এমনকি সেই function এর বাইরে থেকেও।

4. **JavaScript এ Promises কী?**
   - Promise হল asynchronous operation handle করার একটি পদ্ধতি, যা success বা failure এর ভিত্তিতে resolve বা reject হয়।

5. **Async/Await কীভাবে কাজ করে?**
   - `async/await` হল asynchronous code লেখার জন্য একটি syntax, যা promises এর উপরে তৈরি এবং synchronous code এর মতো দেখতে।

6. **JavaScript এ `this` keyword এর অর্থ কী?**
   - `this` keyword সাধারণত যে object এর মধ্যে function call করা হচ্ছে, তাকে reference করে।

7. **JavaScript এ `call()`, `apply()`, এবং `bind()` এর মধ্যে পার্থক্য কী?**
   - `call()` এবং `apply()` function কে call করার সময় `this` এর value নির্ধারণ করে। `call()` আলাদা আলাদা arguments গ্রহণ করে, আর `apply()` একটি array হিসাবে arguments গ্রহণ করে। `bind()` একটি নতুন function তৈরি করে যেখানে `this` স্থির করা হয়।

8. **JavaScript এ Hoisting কী?**
   - Hoisting হল JavaScript এ variables এবং functions এর declarations কে তাদের ব্যবহারের আগে উপরে তুলে আনা হয়।

9. **JavaScript এ Event Loop কী?**
   - Event Loop হল asynchronous operations গুলি manage করার জন্য একটি mechanism, যা call stack এবং callback queue এর মধ্যে সমন্বয় করে।

10. **JavaScript এ IIFE (Immediately Invoked Function Expression) কী?**
    - IIFE হল একটি function যা সঙ্গে সঙ্গে declare এবং execute করা হয়, যেমন: `(function() {})()`।

### **React.js:**

11. **React কী এবং কেন এটি ব্যবহৃত হয়?**
    - React হল একটি JavaScript library, যা user interfaces তৈরি করতে ব্যবহৃত হয়, বিশেষত single-page applications এর জন্য।

12. **React এ Components কী?**
    - Components হল React এর বিল্ডিং ব্লক, যা UI এর পৃথক অংশ তৈরি করে। এটি functional অথবা class ভিত্তিক হতে পারে।

13. **React এর state এবং props এর মধ্যে পার্থক্য কী?**
    - `state` হল component এর নিজস্ব data, যেখানে `props` হল parent component থেকে child component এ pass করা data।

14. **React এর useState Hook কীভাবে কাজ করে?**
    - `useState` হল একটি React Hook, যা functional components এ state পরিচালনা করতে ব্যবহৃত হয়। এটি একটি state variable এবং একটি update function প্রদান করে।

15. **React এর useEffect Hook কী?**
    - `useEffect` হল একটি React Hook, যা side effects পরিচালনা করতে ব্যবহৃত হয়, যেমন data fetching, subscriptions, অথবা DOM manipulation।

16. **React এ Lifecycle Methods কী?**
    - Lifecycle methods হল class components এ নির্দিষ্ট সময়ে invoke হওয়া বিশেষ methods, যেমন `componentDidMount`, `componentDidUpdate`, এবং `componentWillUnmount`।

17. **React এ Context API কী?**
    - Context API হল একটি React feature, যা props drilling ছাড়াই component tree তে data pass করতে দেয়।

18. **React এ Higher-Order Components (HOCs) কী?**
    - HOCs হল একটি pattern, যা একটি component কে enhance করে, এবং নতুন functionalities সহ নতুন component return করে।

19. **React এর Virtual DOM কী?**
    - Virtual DOM হল React এর একটি in-memory representation, যা real DOM এর পরিবর্তে ব্যবহৃত হয়, এবং rendering দ্রুত করে।

20. **React এ Redux কী এবং এটি কেন ব্যবহৃত হয়?**
    - Redux হল একটি state management library, যা application এর state গুলি single source of truth হিসেবে পরিচালনা করতে ব্যবহৃত হয়।

### **HTML:**

21. **HTML এর ডিফল্ট ডকুমেন্ট structure কী?**
    - HTML ডকুমেন্ট structure সাধারণত `<html>`, `<head>`, এবং `<body>` তে বিভক্ত থাকে।

22. **Semantic HTML এর গুরুত্ব কী?**
    - Semantic HTML ব্যবহারকারীর এবং search engines এর জন্য ডকুমেন্ট এর অর্থ বোঝার জন্য সহায়ক হয়, যেমন `<header>`, `<footer>`, `<section>` ইত্যাদি।

23. **HTML5 এর নতুন features কী কী?**
    - HTML5 এর নতুন features এর মধ্যে আছে `<article>`, `<section>`, `<audio>`, `<video>`, `<canvas>`, এবং form validation।

24. **HTML এ `meta` tags এর ব্যবহার কী?**
    - `meta` tags ডকুমেন্ট সম্পর্কে metadata প্রদান করে, যেমন character set, viewport settings, এবং SEO জন্য keywords।

25. **HTML এ `iframe` কী?**
    - `iframe` একটি element, যা একটি web page এর মধ্যে আরেকটি web page embed করতে ব্যবহৃত হয়।

26. **HTML এর `data-*` attributes কী?**
    - `data-*` attributes কাস্টম data attributes, যা HTML elements এ বিভিন্ন data storage করতে ব্যবহৃত হয়, যা JavaScript থেকে access করা যায়।

27. **HTML এ `alt` attribute এর গুরুত্ব কী?**
    - `alt` attribute image elements এ ব্যবহৃত হয়, যা image এর বিকল্প টেক্সট প্রদান করে, এবং accessibility এর জন্য গুরুত্বপূর্ণ।

28. **HTML এর Form Elements এবং Input Types এর মধ্যে পার্থক্য কী?**
    - Form Elements গুলি হল `<form>`, `<input>`, `<textarea>`, `<button>`, ইত্যাদি। Input Types গুলি হল text, password, email, number, file, radio, checkbox ইত্যাদি।

29. **HTML এ `aria-*` attributes এর ব্যবহার কী?**
    - `aria-*` attributes Accessibility for Rich Internet Applications (ARIA) এর অংশ, যা screen readers এবং assistive technologies এর জন্য UI elements এর তথ্য প্রদান করে।

30. **HTML এ `localStorage` এবং `sessionStorage` এর মধ্যে পার্থক্য কী?**
    - `localStorage` ডেটা ব্রাউজার এ indefinitely store করে, যেখানে `sessionStorage` ডেটা শুধুমাত্র session পর্যন্ত store করে।

### **CSS:**

31. **CSS এর Box Model কী?**
    - CSS Box Model হল একটি element এর বিভিন্ন অংশ, যেমন content, padding, border, এবং margin।

32. **CSS এর Flexbox কী এবং এটি কীভাবে কাজ করে?**
    - Flexbox হল একটি CSS layout model, যা elements গুলিকে এক সারিতে অথবা কলামে arrange করতে ব্যবহৃত হয়, এবং flexible layout তৈরি করে।

33. **CSS Grid Layout এর সুবিধা কী?**
    - CSS Grid Layout হল একটি 2D grid system, যা complex layouts সহজে তৈরি করতে সাহায্য করে।

34. **CSS এর Specificity কী এবং এটি কীভাবে কাজ করে?**
    - Specificity হল CSS selectors এর importance এর মাপ, যা determines করে কোন styles গুলি element এ apply হবে।

35. **CSS এর Pseudo-classes এবং Pseudo-elements এর মধ্যে পার্থক্য কী?**
    - Pseudo-classes হল selectors যা element এর current state অনুযায়ী styling করে, যেমন `:hover`, `:active`, `:focus`। Pseudo-elements হল selectors যা element এর অংশ অনুযায়ী styling করে, যেমন `::before`, `::after`।

36. **Responsive Design এর জন্য CSS Media Queries কীভাবে ব্যবহার করা হয়?**
    - Media Queries CSS এ conditions ভিত্তিক styles apply করতে ব্যবহৃত হয়, যেমন screen size, orientation, resolution অনুযায়ী।

37. **CSS এর `position` property এর বিভিন্ন মান কী কী?**
    - `position` property এর বিভিন্ন মান হল `static`, `relative`, `absolute`, `fixed`, এবং `sticky`।

38. **CSS এর `display` property এর মানগুলো কী?**
    - `display` property এর মানগুলি হল `block`, `inline`, `inline-block`, `flex`, `grid`, `none` ইত্যাদি।

39. **CSS এর `z-index` কী এবং এটি কীভাবে কাজ করে?**
    - `z-index` হল একটি stacking order property, যা positioned elements এর overlap নিয়ন্ত্রণ করে।

40. **CSS Preprocessors যেমন SASS/SCSS এর সুবিধা কী?**
    - SASS/SCSS হল CSS Preprocessors, যা variables, nesting, mixins, এবং inheritance এর মতো features প্রদান করে, যা CSS কোডকে আরও modular এবং maintainable করে।

### **TypeScript:**

41. **TypeScript কী এবং কেন এটি ব্যবহৃত হয়?**
    - TypeScript হল JavaScript এর একটি superset, যা static typing এবং additional features প্রদান করে, যা errors ধরতে এবং কোড আরও secure করতে সাহায্য করে।

42. **TypeScript এ `interface` এবং `type` এর মধ্যে পার্থক্য কী?**
    - `interface` এবং `type` TypeScript এ object structure define করতে ব্যবহৃত হয়। `interface` শুধুমাত্র object type describe করতে ব্যবহৃত হয়, যেখানে `type` unions এবং intersections সহ অন্যান্য ধরনের জন্যও ব্যবহৃত হয়।

43. **TypeScript এ Generics কীভাবে কাজ করে?**
    - Generics হল TypeScript এর একটি feature, যা functions, classes, এবং interfaces কে বিভিন্ন ধরনের জন্য reusable করতে দেয়। Generics placeholder type হিসাবে কাজ করে যা নির্দিষ্ট ধরনের সঙ্গে কাজ করতে সক্ষম।

44. **TypeScript এর `enum` কী?**
    - `enum` হল TypeScript এ একটি বিশেষ ধরনের data structure, যা নির্দিষ্ট নামের constants গুলি group করতে ব্যবহৃত হয়। এটি numeric বা string উভয় ধরনের হতে পারে।

45. **TypeScript এ Union Types এবং Intersection Types এর মধ্যে পার্থক্য কী?**
    - Union Types একটি variable কে একাধিক ধরনের মধ্যে যে কোনো একটি হতে দেয়, যেমন `string | number`। Intersection Types একটি variable কে একাধিক ধরনের সমস্ত বৈশিষ্ট্য ধারণ করতে দেয়, যেমন `Type1 & Type2`।

46. **TypeScript এ `never` type কী?**
    - `never` type হল একটি বিশেষ type, যা কখনোই কোনো মান ধারণ করে না। এটি এমন functions এর জন্য ব্যবহৃত হয় যা কখনোই return করে না (যেমন infinite loop বা exceptions)।

47. **TypeScript এ Type Assertion কী?**
    - Type Assertion হল TypeScript এ একটি পদ্ধতি, যা compile time এ compiler কে নির্দিষ্ট করে বলে দেয় যে কোন একটি নির্দিষ্ট type আছে, কিন্তু runtime এ তা পরিবর্তন করা যায় না।

48. **TypeScript এ `readonly` modifier কীভাবে কাজ করে?**
    - `readonly` modifier properties গুলিকে immutable করে দেয়, অর্থাৎ একবার set করার পরে তা পরিবর্তন করা যায় না।

49. **TypeScript এ `Partial`, `Pick`, এবং `Omit` utility types কীভাবে কাজ করে?**
    - `Partial<T>` একটি type এর সমস্ত properties কে optional করে দেয়। `Pick<T, K>` একটি type থেকে নির্দিষ্ট properties select করে। `Omit<T, K>` একটি type থেকে নির্দিষ্ট properties বাদ দেয়।

50. **TypeScript এ `unknown` এবং `any` এর মধ্যে পার্থক্য কী?**
    - `unknown` হল একটি নিরাপদ type, যা type checking বাধ্যতামূলক করে। `any` হল একটি flexible type, যা type checking এড়িয়ে যায় এবং যেকোনো type হতে পারে।

51. **TypeScript এ Decorators কী এবং কিভাবে ব্যবহৃত হয়?**
    - Decorators হল TypeScript এ একটি special type এর syntax, যা classes এবং class members এর উপর code add করতে বা modify করতে ব্যবহৃত হয়।

52. **TypeScript এ Mapped Types কীভাবে কাজ করে?**
    - Mapped Types একটি type এর properties গুলির উপর ভিত্তি করে নতুন types তৈরি করতে ব্যবহৃত হয়। এটি dynamic type construction এর জন্য ব্যবহৃত হয়।

53. **TypeScript এ `this` এর ব্যবহারের সময় কোন সমস্যাগুলি হতে পারে?**
    - TypeScript এ `this` এর context যদি ভুলভাবে bind করা হয়, তাহলে run-time errors ঘটতে পারে। Arrow functions এবং explicit binding এর মাধ্যমে `this` এর context ঠিক রাখা যায়।

### **Redux:**

54. **Redux কী এবং এর মূল ধারণাগুলি কী?**
    - Redux হল একটি predictable state container, যা JavaScript applications এ ব্যবহার করা হয়। এর মূল ধারণাগুলি হল `store`, `actions`, `reducers`, এবং `dispatch`।

55. **Redux এর Single Source of Truth কী?**
    - Redux এ, পুরো application এর state একটি single object tree তে store করা হয়, যা পুরো application এর জন্য একক source হিসেবে কাজ করে।

56. **Redux এ `store` কীভাবে কাজ করে?**
    - `store` হল Redux এর central hub, যেখানে পুরো application's state এবং logic গুলি থাকে। এটি state access, state update, এবং state এর changes এর জন্য subscription পরিচালনা করে।

57. **Redux এ `action` এবং `reducer` এর মধ্যে পার্থক্য কী?**
    - `action` হল একটি plain JavaScript object, যা state পরিবর্তন এর intention বোঝায়। `reducer` হল একটি pure function, যা state এবং action input হিসেবে নিয়ে নতুন state return করে।

58. **Redux Thunk কী এবং এটি কেন ব্যবহৃত হয়?**
    - Redux Thunk middleware হিসাবে কাজ করে, যা action creators এ asynchronous logic (যেমন API calls) পরিচালনা করতে দেয়। এটি functions return করে যা `dispatch` এর মাধ্যমে asynchronous actions পরিচালনা করতে সাহায্য করে।

59. **Redux Saga কী এবং কিভাবে এটি কাজ করে?**
    - Redux Saga একটি middleware, যা asynchronous actions পরিচালনা করতে Generator functions ব্যবহার করে। এটি `sagas` হিসেবে পরিচিত যা side effects পরিচালনা করতে `yield` করে।

60. **Redux Toolkit কী এবং এটি কেন ব্যবহৃত হয়?**
    - Redux Toolkit হল Redux এর জন্য একটি official, opinionated set of tools, যা Redux store এর configuration এবং common use cases এর জন্য boilerplate কমায় এবং development experience সহজ করে।

61. **Redux এ combineReducers() কীভাবে কাজ করে?**
    - `combineReducers()` হল একটি helper function, যা একাধিক reducers কে একটি single reducer function এ combine করতে দেয়।

62. **Redux এ `connect()` function এর কাজ কী?**
    - `connect()` function হল React components কে Redux store এর সাথে যুক্ত করার জন্য ব্যবহৃত একটি HOC, যা state এবং dispatch props হিসেবে component এ pass করে।

63. **Redux এ Middleware কী?**
    - Middleware হল Redux এর একটি layer, যা action dispatch এর আগে বা পরে code execute করতে দেয়, যেমন logging, crash reporting, বা asynchronous requests।

### **MongoDB:**

64. **MongoDB কী এবং কেন এটি ব্যবহৃত হয়?**
    - MongoDB হল একটি NoSQL, document-oriented database, যা JSON-এর মতো BSON (Binary JSON) ডকুমেন্ট ব্যবহার করে data store করতে। এটি schema-less এবং horizontal scalability প্রদান করে।

65. **MongoDB এ Schema কী?**
    - MongoDB নিজে schema-less, কিন্তু Schema design (যেমন Mongoose এর সাহায্যে) ব্যবহার করে, developers ডকুমেন্ট এর data structure নিয়ন্ত্রণ করতে পারেন।

66. **MongoDB এ Indexes কী এবং এর প্রয়োজনীয়তা কী?**
    - Indexes হল database এর একটি data structure, যা data retrieval কে দ্রুত করে। Indexes fields এর উপর create করা হয়, যা search এবং sorting operations দ্রুততর করে।

67. **MongoDB এ Aggregation Framework কী?**
    - Aggregation Framework হল MongoDB এর একটি powerful feature, যা complex data processing এবং transformation এর জন্য data pipeline ব্যবহার করে, যেমন data filtering, grouping, এবং calculating.

68. **MongoDB এ Replica Set কী?**
    - Replica Set হল MongoDB এর একটি feature, যা data redundancy এবং high availability নিশ্চিত করার জন্য একই data এর একাধিক copies (replicas) তৈরি করে।

69. **MongoDB এ Sharding কী?**
    - Sharding হল MongoDB এর horizontal partitioning technique, যা large datasets এবং high-throughput workloads এর জন্য data distribution এবং scalability বৃদ্ধি করে।

70. **MongoDB এ Query Optimization কীভাবে করা হয়?**
    - Query Optimization এর জন্য MongoDB এ indexes তৈরি করা হয়, query patterns analyze করা হয়, এবং query planner ব্যবহার করা হয় যা সবচেয়ে কার্যকর query execution plan নির্বাচন করে।

71. **MongoDB এ Transactions কীভাবে কাজ করে?**
    - MongoDB এ transactions multi-document ACID transactions কে support করে, যা একাধিক operations কে একটি logical unit হিসেবে execute করতে দেয়।

72. **MongoDB এর `find()` method এর কিছু সাধারণ অপশন কী?**
    - `find()` method এর সাধারণ অপশনগুলির মধ্যে আছে `limit`, `skip`, `sort`, `projection`, এবং `filtering`।

73. **MongoDB এ ObjectId কী?**
    - ObjectId হল MongoDB এর primary key এর জন্য একটি unique identifier, যা 12-byte এর BSON type এবং document creation time, machine identifier, এবং process identifier ধারণ করে।

### **Mongoose:**

74. **Mongoose কী এবং এটি কেন ব্যবহৃত হয়?**
    - Mongoose হল MongoDB এর জন্য একটি object modeling tool, যা schema-based data modeling এবং validation প্রদান করে।

75. **Mongoose এ Schema কীভাবে তৈরি করা হয়?**
    - Mongoose এ Schema তৈরি করা হয় একটি new Schema object এর মাধ্যমে, যেখানে fields এবং তাদের types নির্ধারণ করা হয়।

76. **Mongoose এ Model কী?**
    - Model হল Mongoose এর schema থেকে তৈরি হওয়া একটি compiled instance, যা MongoDB collections এর উপর CRUD operations পরিচালনা করতে ব্যবহৃত হয়।

77. **Mongoose এ `populate()` method কীভাবে কাজ করে?**
    - `populate()` method হল একটি Mongoose method, যা references সহ documents এর মধ্যে related data populate করতে ব্যবহৃত হয়।

78. **Mongoose এর Middleware কী এবং এর প্রকারভেদ কী?**
    - Mongoose এর Middleware হল functions যা model এর `save`, `remove`, `update`, এবং `validate` এর মতো operations এর আগে বা পরে execute হয়। Pre এবং Post Middleware এর প্রকারভেদ।

79. **Mongoose এ Virtuals কী?**
    - Virtuals হল Mongoose schema এর একটি feature, যা document এ physical storage ছাড়াই properties তৈরি করে। এগুলি computed properties বা relationships এর জন্য ব্যবহৃত হয়।

80. **Mongoose এ Validators কীভাবে কাজ করে?**
    - Validators হল functions যা Mongoose schema fields এর জন্য data validation নিশ্চিত করে। Custom এবং built-in validators (যেমন `required`, `minLength`, `maxLength`) অন্তর্ভুক্ত।

81. **Mongoose এ `lean()` method কী?**
    - `lean()` method একটি Mongoose query কে simple JavaScript objects return করতে বলে, যা performance উন্নত করে কারণ এটি documents কে Mongoose model instances এ convert করে না।


82. **Mongoose এর Discriminators কী এবং কিভাবে কাজ করে?**
    - Discriminators হল Mongoose এর একটি feature, যা single collection এর মধ্যে বিভিন্ন schema ব্যবহার করার অনুমতি দেয়। এটি inheritance এর মতো কাজ করে, যেখানে একটি base schema থাকে এবং তার উপর ভিত্তি করে অন্যান্য schema তৈরি করা হয়।

83. **Mongoose এ Timestamps কীভাবে enable করা হয়?**
    - Mongoose এ timestamps enable করতে schema definition এ `{ timestamps: true }` অপশন পাস করতে হয়। এটি `createdAt` এবং `updatedAt` fields স্বয়ংক্রিয়ভাবে যোগ করে।

84. **Mongoose এ `findOneAndUpdate()` method কী এবং এটি কীভাবে কাজ করে?**
    - `findOneAndUpdate()` method একটি document খুঁজে বের করে এবং তা update করে। এটি query object এবং update object নেয় এবং optionally একটি configuration object নেয় যা additional options নির্ধারণ করতে পারে।

85. **Mongoose এর `Schema.Types.ObjectId` এর ব্যবহার কী?**
    - `Schema.Types.ObjectId` হল Mongoose এর একটি বিশেষ type, যা MongoDB এর ObjectId এর সাথে map করা হয়। এটি references এবং relational data management এর জন্য ব্যবহৃত হয়।

86. **Mongoose এর Query Helpers কী?**
    - Query Helpers হল custom methods যা Mongoose schema এর মধ্যে define করা যায়, এবং এটি queries কে আরো expressive এবং reusable করে তোলে।

87. **Mongoose এর `save()` method কী এবং কখন এটি ব্যবহার করা হয়?**
    - `save()` method একটি Mongoose model এর instance কে database এ persist করার জন্য ব্যবহার করা হয়। এটি নতুন data insert করতে বা বিদ্যমান data update করতে ব্যবহৃত হয়।

88. **Mongoose এর `toObject()` এবং `toJSON()` methods এর মধ্যে পার্থক্য কী?**
    - `toObject()` method একটি document কে plain JavaScript object এ convert করে এবং `toJSON()` method object কে JSON এর stringified version এ convert করে।

89. **Mongoose এর Schema Options কী কী হতে পারে?**
    - Schema Options এর মধ্যে `timestamps`, `versionKey`, `toObject`, `toJSON`, এবং `id` অন্তর্ভুক্ত, যা schema এর behavior কাস্টমাইজ করতে দেয়।

### **Express.js:**

90. **Express.js কী এবং এটি কেন ব্যবহৃত হয়?**
    - Express.js হল Node.js এর উপর ভিত্তি করে একটি minimal এবং flexible web application framework, যা robust set of features প্রদান করে web এবং mobile applications তৈরি করতে।

91. **Express.js এ Middleware কী এবং এর প্রকারভেদ কী?**
    - Middleware হল functions, যা request এবং response এর মধ্যে execute হয়। এর প্রকারভেদগুলি হল application-level, router-level, error-handling, এবং built-in middleware।

92. **Express.js এ Routing কীভাবে কাজ করে?**
    - Routing হল URL এবং HTTP method এর ভিত্তিতে incoming requests কে handle করার প্রক্রিয়া। Express.js এ routing setup করার জন্য `app.get()`, `app.post()`, `app.put()`, এবং `app.delete()` এর মতো methods ব্যবহার করা হয়।

93. **Express.js এ `req` এবং `res` objects কী এবং এগুলি কীভাবে কাজ করে?**
    - `req` object হল request object, যা client থেকে server এ incoming HTTP request এর data ধারণ করে। `res` object হল response object, যা server থেকে client এ outgoing response এর data পাঠাতে ব্যবহৃত হয়।

94. **Express.js এ Static Files serve করতে কীভাবে কাজ করা হয়?**
    - Static Files serve করার জন্য Express.js এ `express.static` middleware ব্যবহার করা হয়, যা নির্দিষ্ট directory থেকে CSS, JS, এবং images এর মতো static files serve করতে পারে।

95. **Express.js এ Error Handling কীভাবে করা হয়?**
    - Express.js এ Error Handling করার জন্য custom error-handling middleware ব্যবহার করা হয়, যা চারটি arguments (`err`, `req`, `res`, `next`) গ্রহণ করে এবং errors handle করে।

96. **Express.js এ Template Engines কী এবং কেন ব্যবহার করা হয়?**
    - Template Engines হল tools, যা HTML templates এর সাথে dynamic data bind করে। Express.js এ `ejs`, `pug`, বা `handlebars` এর মতো template engines ব্যবহার করা হয় view rendering এর জন্য।

97. **Express.js এ `next()` function কীভাবে কাজ করে?**
    - `next()` function হল Express.js এর একটি middleware function, যা current middleware থেকে পরবর্তী middleware বা route handler এ control pass করতে ব্যবহৃত হয়।

98. **Express.js এ CORS কী এবং কিভাবে সেটাপ করা হয়?**
    - CORS (Cross-Origin Resource Sharing) একটি security feature, যা একটি web application কে অন্য domain থেকে resources request করার অনুমতি দেয়। Express.js এ CORS enable করতে `cors` middleware ব্যবহার করা হয়।

99. **Express.js এ URL Parameters এবং Query Parameters এর মধ্যে পার্থক্য কী?**
    - URL Parameters হল URL এর অংশ, যা route এর অংশ হিসেবে নির্ধারণ করা হয় (`/user/:id`)। Query Parameters হল URL এর শেষের অংশ, যা key-value pairs হিসেবে থাকে (`/search?query=express`)।

100. **Express.js এ `app.listen()` method কী?**
    - `app.listen()` method Express.js application কে নির্দিষ্ট port এ incoming requests শোনার জন্য start করে। এটি server কে শুরু করে এবং application কে externally accessible করে।

101. **Express.js এ RESTful API কীভাবে তৈরি করা হয়?**
    - RESTful API তৈরি করার জন্য Express.js এ routes, controllers, এবং middleware setup করা হয়, এবং HTTP methods (GET, POST, PUT, DELETE) এর মাধ্যমে CRUD operations পরিচালনা করা হয়।

102. **Express.js এ `app.use()` method এর কাজ কী?**
    - `app.use()` method একটি middleware function বা series of middleware functions কে application এ attach করতে ব্যবহৃত হয়, যা সকল incoming requests এর জন্য execute হয়।

103. **Express.js এ Sessions এবং Cookies কিভাবে ব্যবহৃত হয়?**
    - Express.js এ sessions এবং cookies ব্যবহার করা হয় user authentication এবং data persistence এর জন্য। `express-session` middleware session management এবং `cookie-parser` middleware cookie management এর জন্য ব্যবহৃত হয়।
