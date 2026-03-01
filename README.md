📱 1. App Name & Short Description
App Name: A-Level Pathfinder
Short Description: An intelligent advisor that generates personalized A-Level degree pathways based on academic performance and personality.

❓ 2. What problem is your app playground trying to solve and what inspired you to solve it? (Max 200 words)
Tailored specifically for the UK high school curriculum, A-Level Pathfinder addresses the high-stakes transition from GCSEs to A-Levels. This pivotal moment is often navigated with anxiety and external pressure rather than data-driven insight.
Witnessing peers drop out due to mismatched subject choices inspired me to build a tool that decodes the student—not just the syllabus. However, previous solutions required expensive, slow, and privacy-invasive cloud APIs.
The turning point came at WWDC with the release of the Foundation Models framework. This epoch-making API provided the missing link: a powerful on-device AI capable of complex reasoning without an internet connection.
Leveraging this, I built a solution that is real-time, free, and private. It empowers students to instantly visualize personalized "Degree Pathways," turning a daunting administrative hurdle into a confident step toward their future.

🎯 3. Who would benefit from your app playground and how? 
The primary beneficiaries are Year 11 students globally following the British curriculum. Standing at the critical juncture of finishing GCSEs, they face a high-stakes decision: selecting A-Level subjects that define their university future.
Unlike the flexible US system, UK university admissions are notoriously rigid regarding subject prerequisites. A single mismatched choice—such as omitting Chemistry for a Medical degree—can irreversibly disqualify a student from their dream career.
A-Level Pathfinder acts as a crucial safety net. It benefits students by simulating the long-term consequences of their choices before they commit. By strictly aligning their GCSE strengths with university entry standards, the app prevents administrative errors from becoming life-altering regrets. It transforms a source of anxiety into a strategic roadmap, ensuring that today's subject choices keep tomorrow's doors open.

♿️ 4. How did accessibility factor into your design process? 
For me, accessibility means removing barriers—whether infrastructural, visual, or cognitive.
1. Infrastructural Accessibility (Offline-First): Recognizing that high schools often have restrictive firewalls or unstable internet, I engineered the app to be fully offline-capable. By running the AI engine on-device, I ensured that every student has access to instant guidance without connectivity hurdles.
2. Visual & Interactive Accessibility: To support the "family discussion" nature of university planning, I strictly adhered to Dynamic Type guidelines. This ensures that the dense "Strategy Reports" remain legible for parents with declining vision. I also utilized SF Symbols 6 as semantic anchors, helping users decode complex MBTI concepts visually rather than relying solely on text.
3. Cognitive Accessibility: A-Level selection is overwhelming. I employed Progressive Disclosure via NavigationSplitView to break complex decisions into digestible steps. This intuitive design minimizes cognitive load, making the tool approachable for both digital-native students and their guardians.

💻 5. What other technologies did you use in your app playground, and why did you choose them? 
I architected A-Level Pathfinder to leverage the full power of the Apple ecosystem, prioritizing On-Device Intelligence and native fluidity.
 * FoundationModels: I utilized this framework to construct a privacy-first reasoning engine. By leveraging structured generation, the app transforms abstract student data into type-safe Swift objects, ensuring the degree advice is personalized without hallucination risks.
 * SwiftUI & SF Symbols: I employed SF Symbols 6 exclusively to ensure a cohesive, Apple-native aesthetic. I paired this with custom physics-based springs in SwiftUI, giving the interface a tactile, organic weight that mimics real-world interaction rather than static UI.
 * Natural Language: I integrated this framework to semantically analyze user aspirations. This allows the app to map vague interests to concrete degree pathways using linguistic analysis rather than brittle keyword matching.
 * TipKit: To enhance discoverability, I used TipKit to surface contextual guidance precisely when needed. This creates a fluid onboarding experience that respects the user's intelligence without cluttering the screen.

🌟 6. Beyond the Swift Student Challenge 
My journey began in elementary school with Swift Playgrounds, evolving from a curious learner to a dedicated community contributor.
Global Community Leadership:
I have transitioned from a participant to an organizer. This year, I joined SwiftGG, China’s largest Swift developer community. I am proud to serve as a core volunteer organizer for the upcoming "Let's Vision" conference in Shanghai this March. My goal is to bridge the gap between student enthusiasts and professional developers in the spatial computing era.
Engineering & Innovation:
At school, I have been the Technical Lead of the Electric Vehicle Club for three years. I apply my coding skills to solve physical problems—ranging from CAD modeling and vehicle assembly to developing our team’s website and telemetry systems. I also leverage these digital assets to secure sponsorships for our national UK races.
Through these experiences, I demonstrate to my peers that coding is not just about building apps; it is a universal tool for engineering innovation and community building.
