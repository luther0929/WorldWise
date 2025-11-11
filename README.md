# 🌏 WorldWise
A world map travel tracker being built while learning ReactJS advance concepts.

---

## 👀 Preview

<img width="2474" height="1348" alt="image" src="https://github.com/user-attachments/assets/9ffa894a-eb5d-485a-8f8d-48cfad03c4e5" />
<img width="2467" height="1349" alt="image" src="https://github.com/user-attachments/assets/51423a05-26a6-470e-b42f-48fabd066856" />


---

## 🧠 What I Learned
- useContext to remove prop drilling and better manage state
- Passing paramaters through the URL
- Creating useReducer to better manage state logic
- React browser dev tool'S profiler to check rendering performance
- useMemo and useCallback to memoize values and functions
- Lazy loading to reduce JS bundle size

---

## ⚙️ Tech Stack
- ⚛️ **React** – component-based UI
- ⚡ **Vite** – lightweight dev environment

---

## 🧩 Features
- Mock user authentication
- Map navigation using leaflet
- CRUD operations of cities travelled
- Locate position on map using user's GPS location 

---

## 🚀 Getting Started

### Clone the Repository
```bash
git clone https://github.com/luther0929/WordWise.git
cd worldwise
npm install
npm run server
npm run dev
```

---

## 📑 Commit Message Convention
Starting 28/10/2025, this repository follows the Conventional Commits format for better clarity.

### Format
````
<type>(optional scope): <short summary>
````
### Examples
````
feat(ui): add CityList component
fix(styles): remove white scrollbar from sidebar
refactor(context): simplify CityContext reducer logic
docs(readme): update setup instructions
````
### Common Types
| Type       | Description                                 |
| ---------- | ------------------------------------------- |
| `feat`     | New feature or component                    |
| `fix`      | Bug fix or patch                            |
| `refactor` | Code restructure without behavior change    |
| `style`    | Styling or formatting only                  |
| `docs`     | Documentation updates                       |
| `chore`    | Maintenance, tooling, or dependency changes |
| `test`     | Adding or updating tests                    |

### Summary Format

```jsx
<verb> + <what> + (to/for/from) + <where/why>
```

Earlier commits may use simpler messages (e.g., “Added sidebar component”) before adopting this standard, reflecting the project’s evolution toward professional Git workflows.
