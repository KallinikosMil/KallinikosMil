<h1 align="center">Kallinikos Milonakis</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=2800&pause=1200&color=61DAFB&center=true&vCenter=true&width=560&lines=React+Native+%26+React+engineer%2C+Greece;Always+learning;Sending+the+fix%2C+not+the+issue" alt="typing">
</p>

---

### 👋 About me

- 🧑‍💻 React Native, React and TypeScript — three years, mostly mobile and web banking, in a cross-functional team.
- 🧩 I contribute fixes to the libraries I use. I would rather send the fix than the issue.
- ♿ **Accessibility** is the part I have gone deepest into.
- 🌱 Heading toward fullstack.
- 🚧 Building **LocalUp** and finishing a BEng.
- 💬 Ask me about React Native, accessibility, or testing.

### 📫 Contact me

<p align="left">
  <a href="mailto:kallinikosmil@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://www.linkedin.com/in/kallinikos-milonakis/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

<sub>Greece · UTC+3 · Greek (native), English (fluent)</sub>

### 🧰 What I work with

<p align="left">
  <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" alt="Expo">
  <img src="https://img.shields.io/badge/Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white" alt="Redux Toolkit">
  <img src="https://img.shields.io/badge/React_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white" alt="React Query">
  <img src="https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white" alt="Jest">
  <img src="https://img.shields.io/badge/Detox-1A73E8?style=for-the-badge&logo=testinglibrary&logoColor=white" alt="Detox">
  <img src="https://img.shields.io/badge/Storybook-FF4785?style=for-the-badge&logo=storybook&logoColor=white" alt="Storybook">
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase">
  <img src="https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azuredevops&logoColor=white" alt="Azure DevOps">
  <img src="https://img.shields.io/badge/WCAG_2.2-005A9C?style=for-the-badge&logo=w3c&logoColor=white" alt="WCAG 2.2">
</p>

---

## 🔧 Open source

<p align="center">
  <img src="https://img.shields.io/badge/merged-4-2EA043?style=flat-square&labelColor=161B22" alt="4 merged">
  <img src="https://img.shields.io/badge/open-7-1F6FEB?style=flat-square&labelColor=161B22" alt="7 open">
  <img src="https://img.shields.io/badge/IBM_Carbon-3_merged-005A9C?style=flat-square&labelColor=161B22" alt="IBM Carbon">
</p>

Most of these are libraries I use every day. When something breaks I try to send the fix rather than the issue — which usually means reading a codebase I did not write until I understand it well enough to change it safely.

### ✅ Merged

| Project | What was wrong |
|---|---|
| **[IBM Carbon](https://github.com/carbon-design-system/carbon)** · [#22858](https://github.com/carbon-design-system/carbon/pull/22858) | `cds-text-input` — the label was never associated with the input, and helper and error text were wired through `aria-describedby` as a boolean |
| **[IBM Carbon](https://github.com/carbon-design-system/carbon)** · [#22815](https://github.com/carbon-design-system/carbon/pull/22815) | `cds-radio-button` — the `for`/`id` pair did not match, so the label targeted nothing |
| **[IBM Carbon](https://github.com/carbon-design-system/carbon)** · [#22668](https://github.com/carbon-design-system/carbon/pull/22668) | `Modal` — non-alert modals lost their default `dialog` role |
| **[invest-igator](https://github.com/PanagiotisKaraliolios/invest-igator)** · [#80](https://github.com/PanagiotisKaraliolios/invest-igator/pull/80) | Five silent correctness bugs across portfolio maths, API keys, import and charts — each with a reproduction test |

<sub>Three separate Carbon maintainers merged those three, and five distinct people reviewed them. A shared component that produces wrong semantics does it for every consumer downstream at once.</sub>

### 🔄 Open

| Project | What was wrong |
|---|---|
| **[react-native-paper](https://github.com/callstack/react-native-paper)** · [#5054](https://github.com/callstack/react-native-paper/pull/5054) <br> ![approved](https://img.shields.io/badge/approved-2EA043?style=flat-square&labelColor=161B22) | The Babel plugin emitted Windows path separators into import specifiers. Added a Windows CI job so it stays fixed |
| **[react-native-community/cli](https://github.com/react-native-community/cli)** · [#2827](https://github.com/react-native-community/cli/pull/2827) | `yarn build` silently emitted no JavaScript on Windows — all 55 unit suites failed to start as a result |
| **[Ignite](https://github.com/infinitered/ignite)** · [#3040](https://github.com/infinitered/ignite/pull/3040) | `pnpm test` could not start on Windows: POSIX inline env-var syntax, setting a variable that had been dead since ts-jest dropped the check |
| **[Re.Pack](https://github.com/callstack/repack)** · [#1450](https://github.com/callstack/repack/pull/1450) | Five tests compared platform-native paths to POSIX literals, so the suite was red on Windows against correct code |
| **[Medusa](https://github.com/medusajs/medusa)** · [#16269](https://github.com/medusajs/medusa/pull/16269) | The inventory item was never created when `manage_inventory` was flipped on |
| **[react-navigation](https://github.com/react-navigation/react-navigation)** · [#13197](https://github.com/react-navigation/react-navigation/pull/13197) | `TabView`'s pager drifted out of sync with a controlled `index` |
| **[IBM Carbon](https://github.com/carbon-design-system/carbon)** · [#22711](https://github.com/carbon-design-system/carbon/pull/22711) | `Textarea` — the input was never described by its helper text |

---

## 🚧 Building

**[LocalUp](https://github.com/KallinikosMil/localup-app)** — a location-based app, sole developer.
Expo · React Native · TypeScript · Redux Toolkit · React Query · Supabase · i18next.
My BEng thesis, currently being prepared for release.
