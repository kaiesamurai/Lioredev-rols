
# Lioredev — Connecting Creators, Building Community

## Description

Lioredev is a Web3 application that merges the power of blockchain technology with the simplicity of social connections. The platform empowers creators, supports their work, and makes it easier than ever to give and receive donations.

## Inspiration

The inspiration behind Lioredev came from the desire to create a platform where creators can easily connect with their audience, receive support, and share their work without the complexities often associated with blockchain technology. We wanted to build a community-focused application that leverages the benefits of Web3 while maintaining user-friendliness.

## What it does

Lioredev allows creators to share their content and receive donations seamlessly. By leveraging blockchain technology, the platform ensures transparency and security in transactions. Users can create profiles, share links to their work, and supporters can easily send donations to their favorite creators.

## How we built it

Lioredev was built using the Linera SDK, which provided the necessary tools to integrate blockchain functionality. The frontend was developed with JavaScript and Node.js, while Rust was used for the backend to ensure performance and reliability. The deployment and setup scripts were written in Shell to automate the process.

## Challenges we ran into

During the development of Lioredev, we faced several challenges:
- Integrating blockchain technology in a user-friendly way
- Ensuring secure and transparent transactions
- Optimizing performance for a seamless user experience
- Coordinating between multiple development tools and languages

## Accomplishments that we're proud of

We are proud of several key accomplishments:
- Successfully integrating blockchain technology with a simple and intuitive user interface
- Building a robust and secure platform for creators to receive support
- Automating the deployment process to make it easier for developers to get started
- Creating a community-focused application that empowers creators

## What we learned

Throughout the development of Lioredev, we learned a lot about:
- The intricacies of blockchain technology and its practical applications
- The importance of user experience in the adoption of new technologies
- Effective ways to automate deployment and setup processes
- The value of community and support in the creative industry

## What's next for Lioredev

Looking forward, we have several exciting plans for Lioredev:
- Expanding the platform's features to include more ways for creators to engage with their audience
- Enhancing the user interface and experience based on user feedback
- Collaborating with more creators to understand their needs and improve the platform
- Exploring additional blockchain functionalities to provide even more value to our users

## Deployment

### Prerequisites

- Install Rust
- Install Linera
- Install Node.js

### Steps

1. **Start Local Network**
   Initialize local variables `LINERA_WALLET` and `LINERA_STORAGE`:
   ```bash
   linera net up
   ```

2. **Clone the Repository**
   Clone this repository to your local machine:
   ```bash
   git clone <repository-url>
   ```

3. **Run Deployment Script**
   Navigate to the working directory and execute the deployment script:
   ```bash
   ./scripts/simple.sh <working directory>
   ```
   Example:
   ```bash
   ./scripts/simple.sh /tmp/.tmpguVRWj
   ```

4. **Start Frontend**
   Navigate to the frontend directory, install dependencies, and start the development server:
   ```bash
   cd frontend
   npm install
   npm run dev
   ```

5. **Enjoy**
   Open your browser and enjoy the application.

## About

Lioredev — social application on Linera

## Resources

- [Readme](README.md)
- [Activity](activity-url)

## Repository Statistics

- **Stars:** 0
- **Watchers:** 1
- **Forks:** 0

## Languages Used

- **JavaScript:** 51.9%
- **Rust:** 40.6%
- **Shell:** 6.2%
- **CSS:** 1.3%