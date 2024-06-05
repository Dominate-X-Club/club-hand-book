### Overview of the Dominate X Club App

The Dominate X Club app is designed to create a thriving community for freelancers, digital nomads, and professionals. It helps members develop their skills, find work opportunities, and collaborate on projects. The app also facilitates networking and mentorship, providing a comprehensive ecosystem for personal and professional growth.


## Dev Stages

### MVP: Joining: 5 June - 30 June 2024

#### Code Effort

- [ ] [Simple Landing Page](./landing-page.md)
   - [ ]  Figma Design - Abhinav, Prakrati [Hands On] - Others guide
   - [ ]  React - **$5 Bounty**
- [ ] Sign Up 
   - [ ] Figma Design
   - [ ] Live Discord Explainer - Supabase Auth + Next Middleware - Ashish
   - [ ] React - Good First Issue
- [ ] Login - Good First Issue
   - [ ] Figma Design
   - [ ] Live Discord Explainer - Supabase Auth + Next Middleware - Ashish
   - [ ] React - Good First Issue
- [ ] [Fill Resume](./complete-profile-resume.md)
   - [ ] Supabase DB - Abhinav + Ashish
   - [ ] Figma - Abhinav + Prakrati
   - [ ] React - **$10 Bounty**
- [ ] Join Process -> **Invite:** [Discord Server Link]()   **Win a Bounty:** [Active Bountries Discord Channel](https://discord.gg/MdGKGbYw)
   - [ ] Figma - Abhinav + Prakrati
   - [ ] React - **$5 Bounty** - Beginner Bounty: Only for someone who hasn't already won a bounty

- [ ] User Roles: Visiter -> Applicant |Joining Screen Lock| -> Member -> Mentor -> Squad Founding Mentor -> Steering Squad

#### Learning Track Effort

Live on Discord + Youtube + Twitter

##### Open For All - 14+
- [ ] Open Source for dummies (Non Coders can also understand): Git, Github, Commits, Push, Pull, Pull Request: Hands On Club handbook -> Plus ask users to give star, fork and PR with their member page: T:Abhinav(Intro)+Ashish(Depth) S: Prakrati + Somith
- [ ] Figma - T: Manu Arya S: Abhinav, Prakrati

##### Techies - Freshers/College Grads/School Student - 16+
- [ ] Full Stack with React & Its Ecosystem: T:Ashish S:Abhinav, Shishu, Somith
- [ ] TailwindScss + Shadcn
- [ ] Supabase - Auth & DB: T:Ashish S:Abhinav,Shishu, Somith


## V1: Inviting

- [ ] Home Page
- [ ] Invitation Generation (Where an existing members generates a new invitation, after giving initial data about invitee, limited invites per month - according role in the club)
- [ ] Redeem Invitation (where a new user enters a string of invitation code)
- [ ] Invitation Permalink (Dedicated Page + Social Preview)

## V2: Profiles

- [ ] Profile Page (will show: Image, Name, Resume in various tabs, No Rank, Roles or Badges)
- [ ] Members Page (list of members, along with their role in the club)

## V2: Bounty

- [ ] Bounties Page
- [ ] Bounty Page (Details About the bounty)
- [ ] Add Bounty (Only by steering squad)
- [ ] Update Bounty
- [ ] Auto Post (When bounty is added, auto posts of twitter & discord)

## VL: App Deployment

- [ ] Prepare App Store Assets
- [ ] Pack with ionic/capacitor to APP 

## VM: Learning Track

- [ ] 



## VN: Business

- [ ] Add Bounty (Anyone, by paying club a x% fees -> All of $5 will be cut, x% with bounty compl, y% with no completion)

### Key Features

1. **Profile Setup and Management**
2. **Membership Invitation and Bounty Completion**
3. **Training and Skill Development**
4. **Bounties and Projects**
5. **Community and Networking**
6. **Notifications and Messages**

### Detailed Features and User Flow

#### 1. Profile Setup and Management

**Purpose**: To create a detailed, public profile that serves as a CV for prospective clients and collaborators.

**User Flow**:
1. **Sign-Up/Login**: Users sign up or log in using their Twitter account.
2. **Profile Setup**:
   - **Step 1: Auto-Fill Basic Information**: Profile picture and name are auto-filled from Twitter.
   - **Step 2: Contact Information**: Users add email, phone number, city, and address.
   - **Step 3: Skills and Bio**: Users list their skills and write a brief bio/introduction.
   - **Step 4: Social Media and Portfolio**: Optional fields for social media links and portfolio/website.
   - **Step 5: Professional Goals/Interests**: Users specify what they are seeking from the club and their professional goals.
   - **Step 6: Work Experience**: Users enter current and previous job details.
   - **Step 7: Education**: Users list their educational background.
   - **Step 8: Certificates and Testimonials**: Users can add links or images of certificates and testimonials, along with descriptions.
   - **Step 9: Availability for Work**: Users indicate if they are available for work and specify the types of work they are interested in (freelance, internships, full-time, part-time, other).

**Profile Visibility**: Users are informed that their profile will be public and serve as their CV for prospective clients.

#### 2. Membership Invitation and Bounty Completion

**Purpose**: To ensure new users are vetted and integrated into the community through existing members and task completion.

**User Flow**:
1. **Post Profile Setup**: Users see the requirements to become a full member.
2. **Get an Invite**: 
   - **View Members**: Users can see a list of community members with social media links.
   - **Request Invite**: Users contact a member via social media to request an invitation code.
   - **Enter Invitation Code**: Users enter the received code to complete step one.
3. **Win a Bounty**:
   - **View Active Bounties**: Users browse and select bounties to complete.
   - **Complete Bounty**: Users work on and submit bounty tasks.
   - **System Update**: The system auto-updates when a bounty is won.
4. **Full Membership Confirmation**: Once both steps are completed, the user is granted full access.

#### 3. Training and Skill Development

**Purpose**: To help members enhance their skills and gain certifications.

**User Flow**:
1. **Live Classes**: Users can join scheduled live training sessions.
2. **Recorded Sessions**: Users access a library of recorded training sessions.
3. **Create Content**: Members can create and share training content.

#### 4. Bounties and Projects

**Purpose**: To provide work opportunities and promote collaboration.

**User Flow**:
1. **Available Bounties**: Users browse a list of active bounties with descriptions and rewards.
2. **My Bounties**: Users track the status of their applied and completed bounties.
3. **Project Collaboration**: Tools for managing and participating in collaborative projects.

#### 5. Community and Networking

**Purpose**: To foster a supportive and interactive community.

**User Flow**:
1. **Squads**: Users join small groups (squads) based on interests and goals.
2. **Meetups**: Users can join virtual and in-person meetups.
3. **Inter-Squad Competitions**: Members participate in and view results of competitions.
4. **Member Directory**: Users search and browse other members to connect and collaborate.

#### 6. Notifications and Messages

**Purpose**: To keep users informed and facilitate communication.

**User Flow**:
1. **Notifications**: Real-time alerts for new bounties, project updates, training sessions, and community news.
2. **Messages**: Users can manage their inbox, sent messages, and compose new messages.

### Interface Design

**Mobile and Desktop Consistency**:
- **Bottom Navigation (Mobile)** and **Top Navigation (Desktop)**: Home, Bounties, Training, Community, Notifications.
- **Profile Picture Menu**: Access additional features and settings.
- **Left Sidebar (Desktop)**: Reflects primary navigation options similar to mobile for ease of use.

### Summary

The Dominate X Club app is designed to streamline the process of joining and integrating into a community of freelancers and professionals. It provides tools for skill development, project collaboration, and networking, ensuring users have the resources they need to grow professionally. The app's intuitive navigation and multi-step profile setup process ensure a smooth and engaging user experience, fostering a vibrant and supportive community.
