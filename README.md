# 🚀 WeWard - Interview Challenge

## Goal
Build a lightweight version of the WeWard app onboarding flow that demonstrates your understanding of building funneled onboarding flows, permission handling, and data persistence in React Native.
You can use any third-party libraries/npm packages that you want to use.

![mockup.png](mockup.png)

[Link to Figma file](https://www.figma.com/design/DBpxuwg6Ycw4HHahe6smUQ/Onboarding---usecase?node-id=1-2295&t=LE3TKoOBH6hZ8Wmt-0)

## Challenge Requirements

### Core Features
Implement a complete onboarding experience that includes:

1. **Splash Screen**
   - Initial loading screen with branding

2. **Welcome/Get Started Screen**
   - Introduce the app with compelling messaging
   - **Request Push Notification permission on this first onboarding screen**
   - Explain the value proposition for allowing notifications

3. **User Information Collection**
   - Capture user's name (text input)   
   - Include basic form validation

4. **Permission Requests**   
   - **App Tracking Transparency (ATT)**: Request tracking permission (iOS)
   - Handle both granted and denied states gracefully

5. **Onboarding Completion**
    - Display a completion screen with a thank you message

6. **Home Page**
   - Display personalized greeting with user's name
   - Show step count or activity metric (can be static/fake data)
   - This is where users land after completing onboarding

7. **Data Persistence & Flow Control**
   - Save all collected user data to local storage
   - **Onboarding should only play on first launch**
   - On subsequent app opens, users should land directly on the Home Page


## Evaluation Criteria

We'll be assessing, in order of importance:
1. **Code Architecture and quality**: How well you have structured your code and how easy it is to maintain and extend.
2. **Platform Awareness**: Proper handling of iOS vs Android differences
3. **User Experience**: Flow smoothness, visual design


## Deliverable and Submission
- Working React Native application
- Upload your project to a public repository and share the link with us.

## Bonus Points
- Add animations or transitions between screens
- **Allow users to resume onboarding from their last completed step if they exit mid-flow**


## Installation
Follow the Get Started guide in the Expo documentation to initialize your project.  
**https://docs.expo.dev/get-started/create-a-project/**

You can find all the necessary images in the `images` folder.

---

**Note**: Feel free to use Expo or bare React Native. 