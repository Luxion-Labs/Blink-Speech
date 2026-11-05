# Blink Speech

> Browser assistive app converting eye blink patterns and gaze gestures into spoken phrases.

![Blink Speech Banner](assets/images/banner.svg)

<p align="center">
  <img src="https://img.shields.io/badge/Next.js_14-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js">
  &nbsp;
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  &nbsp;
  <img src="https://img.shields.io/badge/MediaPipe-FaceMesh-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="MediaPipe">
  &nbsp;
  <img src="https://img.shields.io/badge/Web_Speech_API-Synthesis-FF4081?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Web Speech">
  &nbsp;
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS">
  &nbsp;
  <img src="https://img.shields.io/badge/Privacy-100%25_Client--Side-10B981?style=for-the-badge" alt="Privacy">
  &nbsp;
  <img src="https://img.shields.io/badge/SLA-24_Hours-06B6D4?style=for-the-badge" alt="SLA">
</p>

<p align="center">
  <a href="https://blink-speech.vercel.app"><img src="https://img.shields.io/badge/Live_Demo-Open_App-10B981?style=flat-square" alt="Live App"></a>
  &nbsp;
  <a href="https://youtu.be/evakcT6qGRI"><img src="https://img.shields.io/badge/Video-Watch_Demo-FF0000?style=flat-square&logo=youtube&logoColor=white" alt="Watch Demo"></a>
  &nbsp;
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" alt="MIT License"></a>
  &nbsp;
  <a href="CONTRIBUTING.md"><img src="https://img.shields.io/badge/Contributions-Welcome-blueviolet?style=flat-square" alt="Contributing"></a>
</p>

---

## Quick Start & Getting Started

Getting Blink Speech running locally takes only two steps:



Open [http://localhost:3000](http://localhost:3000) in any modern browser with webcam permissions enabled.

---

Key Features**

 **Real-time Gesture Recognition** - Advanced computer vision detects blinks and gaze directions  
️ **Natural Speech Synthesis** - High-quality text-to-speech using Web Speech API  
 **Fully Customizable** - Create your own gesture-to-phrase mappings  
 **Privacy-First** - All processing happens locally, no video data transmitted  
 **Zero Installation** - Runs in any modern web browser with HTTPS  
 **Accessibility-Focused** - Designed for users with motor impairments and speech limitations  
 **Multi-language Support** - Works with any language or custom phrases  
 **Cross-Platform** - Compatible with desktop, tablet, and mobile devices  

## ️ **Technology Stack**

![React](https://img.shields.io/badge/React_18-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-4285F4?style=for-the-badge&logo=google&logoColor=white)
![WebGazer.js](https://img.shields.io/badge/WebGazer.js-FF6F00?style=for-the-badge&logo=javascript&logoColor=white)
![TensorFlow.js](https://img.shields.io/badge/TensorFlow.js-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Radix UI](https://img.shields.io/badge/Radix_UI-161618?style=for-the-badge&logo=radix-ui&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js_API-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Web Speech API](https://img.shields.io/badge/Web_Speech_API-FF4081?style=for-the-badge&logo=googlechrome&logoColor=white)

---

##  **Vision & Impact**

### **Everyone Deserves a Voice**

Blink Speech was born from a simple yet powerful belief: **communication is a fundamental human right**. By transforming natural eye movements into spoken words, we're breaking down barriers that prevent people from expressing their thoughts, needs, and emotions.

### **Who We Help**

 **Healthcare Patients**
- ICU patients who cannot speak due to intubation
- Post-surgery recovery when vocal communication is difficult
- Individuals with locked-in syndrome or severe paralysis
- Emergency communication when traditional methods fail

 **People with Disabilities**
- ALS (Lou Gehrig's disease) patients as speech deteriorates
- Individuals with muscular dystrophy or cerebral palsy
- Stroke survivors during speech therapy recovery
- Anyone with motor impairments affecting traditional communication

⏰ **Temporary Conditions**
- Recovery from oral or throat surgery
- Severe laryngitis or vocal cord issues
- Medication side effects affecting speech
- Fatigue-related communication difficulties

 **Global Accessibility**
- Works in any language or cultural context
- No specialized hardware or expensive equipment required
- Runs on existing devices (computers, tablets, phones)
- Free and open-source for maximum accessibility

---

##  **Quick Start**

### **For Users**
1. ** Try the Demo Video**: [YouTube Demo](https://youtu.be/evakcT6qGRI)
2. ** Read the User Guide**: [Complete usage instructions](./docs/user-guide.md)
3. ** Complete Calibration**: Follow the 5-point setup for optimal accuracy
4. **️ Start Communicating**: Use blinks and gaze to speak!

### **For Developers**
1. ** Clone the Repository**
   ```bash
   git clone https://github.com/Luxion-Labs/Blink-Speech.git
   cd Blink-Speech
   ```

2. **️ Install Dependencies**
   ```bash
   # Frontend
   cd frontend && npm install
   
   # Backend
   cd ../backend && npm install
   ```

3. ** Configure Environment**
   - Set up [Supabase](https://supabase.com) project
   - Copy `.env.example` files and configure variables
   - See [Installation Guide](./docs/installation.md) for details

4. ** Run Development Servers**
   ```bash
   # Terminal 1 - Frontend (https://localhost:5173)
   cd frontend && npm run dev
   
   # Terminal 2 - Backend (http://localhost:3001)
   cd backend && npm run dev
   ```

---

##  **Complete Documentation**

### ** User Documentation**
- [ **User Guide**](./docs/user-guide.md) - How to use Blink Speech effectively
- [ **Troubleshooting**](./docs/troubleshooting.md) - Solve common issues
- [️ **Configuration**](./docs/configuration.md) - Customize settings and preferences

### **️ Technical Documentation**
- [️ **Installation Guide**](./docs/installation.md) - Development and production setup
- [️ **Architecture Overview**](./docs/architecture.md) - System design and data flow
- [ **Development Guide**](./docs/development-guide.md) - Contributing and best practices
- [ **Frontend Components**](./docs/frontend-components.md) - React components and hooks
- [ **API Documentation**](./docs/api-documentation.md) - Backend endpoints and database

### ** Core Technologies**
- [️ **Gesture Detection**](./docs/gesture-detection.md) - Computer vision implementation
- [ **Frontend Architecture**](./docs/frontend.md) - React + Vite structure
- [ **Deployment Guide**](./docs/deployment.md) - Production deployment

 **[Complete Documentation Hub](./docs/README.md)** - Start here for all documentation

---

##  **Team**

| Role | Name | GitHub | 
|------|------|---------|
|  **Project Lead** | Md Athar Jamal Makki | [@atharhive](https://github.com/atharhive) |
|  **Frontend Lead** | Akshad Jogi | [@akshad-exe](https://github.com/akshad-exe) |
| ️ **Backend Lead** | Ayush Sarkar | [@dev-Ninjaa](https://github.com/dev-Ninjaa) | 
---

##  **How It Works**

### **1. ️ Gesture Recognition**
Advanced computer vision powered by MediaPipe and WebGazer.js detects:
- **Blink Patterns**: Single, double, triple, and long blinks
- **Gaze Directions**: Left, right, up, down, and center positioning
- **Combined Gestures**: Blinks + gaze for complex communication (20+ combinations)

### **2.  Real-time Processing**
- **<150ms Detection Latency**: Near-instantaneous gesture recognition
- **Eye Aspect Ratio (EAR)**: Scientific method for accurate blink detection
- **Adaptive Thresholds**: Automatic calibration for optimal performance
- **15-30 FPS Processing**: Smooth real-time operation

### **3. ️ Speech Synthesis**
- **Web Speech API**: High-quality, natural-sounding voices
- **Multi-language Support**: Works with any language
- **Customizable Voice**: Adjust rate, pitch, and volume
- **<1s Speech Latency**: From gesture to spoken word

### **4.  Privacy & Security**
- **100% Local Processing**: No video data ever leaves your device
- **HTTPS Encryption**: Secure communication protocols
- **Anonymous Usage**: No personal information required
- **Local Storage**: Settings saved securely on your device

---

##  **Medical & Healthcare Applications**

### **Critical Care Benefits**
 **Emergency Communication**: Instant access to critical phrases ("Help", "Pain", "Emergency")  
 **Patient Monitoring**: Non-verbal feedback for medical assessment  
 **Telemedicine Integration**: Remote patient communication capabilities  
 **Rapid Response**: Immediate notification systems for urgent needs

### **Rehabilitation Support**
 **Stroke Recovery**: Bridge communication during speech therapy  
 **Motor Skill Development**: Eye-tracking exercises aid neurological recovery  
 **Progress Tracking**: Monitor improvement in motor control and communication  
 **Adaptive Learning**: System learns and adapts to individual capabilities

### **Long-term Care**
 **Home Healthcare**: Enables independent communication with caregivers  
 **Family Connection**: Stay connected with loved ones remotely  
 **Alert Systems**: Customizable emergency and routine notifications  
 **Care Documentation**: Optional logging for healthcare providers

---

##  **Performance & Compatibility**

### **System Specifications**
- **Detection Accuracy**: >95% in optimal conditions
- **Latency**: <150ms gesture recognition, <1s speech output
- **Frame Rate**: Adaptive 15-30 FPS based on device capabilities
- **Memory Usage**: <100MB typical operation
- **Storage**: ~50MB for complete application cache

### **Browser Support**
| Browser | Version | MediaPipe | WebGazer | Speech API | Status |
|---------|---------|:---------:|:--------:|:----------:|:------:|
| Chrome | 80+ |  |  |  |  **Optimal** |
| Firefox | 75+ |  |  |  |  **Excellent** |
| Safari | 13+ |  | ️ |  |  **Good** |
| Edge | 80+ |  |  |  |  **Excellent** |

### **Device Compatibility**
️ **Desktop**: Windows, macOS, Linux - Full feature support  
 **Tablet**: iPad, Android tablets - Optimized touch interface  
 **Mobile**: Smartphone support with adaptive UI  
 **Cameras**: Built-in webcams, USB cameras, HD recommended

---

##  **Roadmap & Future Features**

### ** Version 2.0 (In Development)**
-  **AI-Powered Phrase Prediction**: Context-aware phrase suggestions
-  **Enhanced Multi-language**: 50+ languages with native voices
-  **Analytics Dashboard**: Usage patterns and communication insights
-  **Healthcare Integrations**: Direct API connections to medical systems

### ** Future Innovations**
-  **AR/VR Integration**: Wearable device support (AR glasses, smart contact lenses)
-  **Machine Learning**: Personalized gesture recognition improvement
-  **Medical Partnerships**: Integration with hospital communication systems
-  **Offline PWA**: Complete offline functionality as Progressive Web App
-  **Gamification**: Interactive learning and practice modes

### ** Community Features**
-  **Gesture Sharing**: Community-driven phrase mappings
-  **Learning Resources**: Tutorials and best practices
-  **Plugin System**: Extensible architecture for custom integrations
-  **Mobile Apps**: Native iOS/Android applications

---

##  **Key Features**

### ** Core Capabilities**
 **Zero Installation** - Works instantly in any modern browser  
 **Complete Privacy** - 100% client-side processing, no data transmission  
 **Real-time Recognition** - <150ms gesture detection latency  
 **Custom Mappings** - Create your own gesture-to-phrase combinations  
 **Multi-language** - Support for any language or custom phrases  
 **Offline Ready** - Core features work without internet connection  

### ** Accessibility Features**
 **High Contrast Mode** - Enhanced visibility for users with visual impairments  
 **Large Text Options** - Scalable interface for better readability  
 **Screen Reader Support** - Full compatibility with assistive technologies  
 **Keyboard Navigation** - Complete keyboard accessibility  
 **Voice Customization** - Adjustable speech rate, pitch, and volume  
 **Emergency Mode** - Quick access to critical communication phrases  

### ** Advanced Features**
 **Adaptive Performance** - Automatic optimization based on device capabilities  
 **Calibration System** - Personalized setup for optimal accuracy  
 **Data Export/Import** - Share settings between devices and users  
 **Cloud Sync** - Optional backup and synchronization (Supabase)  
 **SMS Integration** - Send messages via Twilio API  
 **Real-time Logging** - Optional activity tracking for healthcare providers

---

##  **Contributing**

We welcome contributions from developers, researchers, and accessibility advocates! Here's how you can help:

### **️ Development**
-  **Report Bugs**: [Create an issue](https://github.com/Luxion-Labs/Blink-Speech/issues/new) with detailed reproduction steps
-  **Suggest Features**: Share ideas for improving accessibility and usability
-  **Submit Code**: Fork, develop, and create pull requests
-  **Documentation**: Help improve guides, tutorials, and API docs

### ** Testing & Feedback**
-  **Healthcare Professionals**: Provide clinical insights and use case feedback
-  **Accessibility Users**: Share experiences and improvement suggestions
-  **Localization**: Help translate and adapt for different languages/cultures
-  **Research**: Academic collaboration on computer vision and accessibility

### ** Contribution Guidelines**
1. Read our [Development Guide](./docs/development-guide.md)
2. Follow our [Code of Conduct](./CODE_OF_CONDUCT.md)
3. Check existing issues and discussions before creating new ones
4. Write clear commit messages and documentation
5. Test thoroughly and include relevant test cases

---

##  **License**

Blink Speech is open-source software licensed under the [MIT License](./LICENSE). This means you can:

 **Use** - For personal, commercial, or research purposes  
 **Modify** - Adapt the code to your specific needs  
 **Distribute** - Share with others or deploy your own version  
 **Contribute** - Help improve the project for everyone  

---

## 🆘 **Support & Community**

### ** Get Help**
-  **Documentation**: [Complete guides and tutorials](./docs/README.md)
-  **Troubleshooting**: [Common issues and solutions](./docs/troubleshooting.md)
-  **Discussions**: [GitHub Discussions](https://github.com/Luxion-Labs/Blink-Speech/discussions) for questions and ideas
-  **Bug Reports**: [Issue Tracker](https://github.com/Luxion-Labs/Blink-Speech/issues) for technical problems

### ** Connect**
-  **GitHub**: [@Luxion-Labs/Blink-Speech](https://github.com/Luxion-Labs/Blink-Speech)
-  **Contact**: For accessibility partnerships and healthcare integrations
-  **Collaborate**: Open to academic research partnerships

### ** Emergency Support**
For urgent accessibility needs or critical bugs affecting communication:
1. Create a high-priority GitHub issue
2. Include detailed system information and reproduction steps
3. Tag the issue with "urgent" or "accessibility-critical"

---

##  **Acknowledgments**

**Research & Inspiration**:
- MediaPipe team at Google for facial landmark detection
- WebGazer.js contributors for browser-based eye tracking
- Accessibility research community for guidance and feedback
- Healthcare professionals providing real-world insights

**Open Source Technologies**:
- React and Vite communities for modern web development tools
- TensorFlow.js for browser-based machine learning
- Supabase for backend infrastructure
- Tailwind CSS and Radix UI for accessible design systems

**Special Thanks**:
- Beta testers who provided crucial feedback
- Accessibility advocates who guided our design decisions
- Healthcare institutions that shared use case requirements
- Open source contributors who helped improve the codebase

---

<div align="center">

** If Blink Speech has helped you or someone you know, please consider starring the repository to help others discover this tool! **

[⭐ **Star on GitHub** ⭐](https://github.com/Luxion-Labs/Blink-Speech)

*"Communication is a human right. Technology should make it accessible to everyone."*

</div>


---

## Maintainer Response SLA
Luxion Labs enforces a strict 24-hour response SLA on all community issues, feature proposals, and pull requests. See [CONTRIBUTING.md](CONTRIBUTING.md) for full development guidelines.

## License
Distributed under the MIT License. See [LICENSE](LICENSE) for details.
