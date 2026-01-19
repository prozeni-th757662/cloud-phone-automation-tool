# DOCS.md

## Cloud Phone Automation Tool - MadHub Documentation

### MadHub: Powerful Automation Features
MadHub's advanced automation features provide a robust solution for managing social media interactions on platforms like Facebook, Instagram, and TikTok. Specifically designed for cloud phone environments, MadHub enables users to execute automated operations seamlessly, ensuring continuous engagement without requiring constant oversight. 

### Featured Capabilities

#### 1. Facebook Account Warm-Up
The **Facebook Account Warm-Up** feature simulates genuine user activity by browsing homepage feeds and video pages. It intelligently skips over advertisement videos while supporting interactions such as likes and comments. This feature allows users to set custom interaction and execution probabilities, effectively enhancing account activity and reducing the risk of account bans. 

**Primary Capabilities:**
- Simulates real user behavior
- Configurable interaction probability 
- Supports like and comment operations
- Reduces account ban risks by enhancing trustworthiness

#### 2. Facebook Auto-Reply
MadHub's **Facebook Auto-Reply** feature provides the capability to automatically detect and respond to unread messages on Facebook. Users can configure it to work in both input and file modes, allowing for dynamic responses based on incoming messages. The feature can also delete messages post-sending and can be set to operate on intervals, making it suitable for businesses needing 24/7 customer service.

**Primary Capabilities:**
- Automatically replies to messages
- Flexible operation modes (input/file mode)
- Configurable operation intervals
- Enhances customer service responsiveness

### Technical Usage

#### Facebook Account Warm-Up
To utilize the **Facebook Account Warm-Up** feature, follow these instructions:

1. **Initialization**: Install MadHub on your desired platform (cloud phone or emulator).
2. **Feature Activation**: Navigate to the "Facebook Account Warm-Up" section within the MadHub interface.
3. **Configure Interaction Parameters**:
   - **Set Interaction Probability**: Determine the likelihood of interactions (likes/comments); for example, a 70% interaction probability means 70% of browsing sessions will engage with content.
   - **Execution Probability Distribution**: Establish how frequently these interactions should occur during a session.

```java
// Example configuration in pseudocode
setInteractionProbability(70); // Set interaction probability to 70%
setExecutionProbabilityDistribution(15, 20); // Set execution distribution
```

#### Facebook Auto-Reply
To configure the **Facebook Auto-Reply** feature:

1. **Access the Auto-Reply Settings**: Once in the MadHub interface, select the "Facebook Auto-Reply" option.
2. **Choose Operation Mode**: Select between input mode for customized responses or file mode for pre-set responses.
3. **Set Interval Parameters**: Configure how often the bot should check for new messages and respond.

```java
// Example configuration in pseudocode
setOperationInterval(5); // Set interval to check messages every 5 minutes
setResponseMode(input); // Choose dynamic response mode
```

### Configuration Examples

#### Facebook Account Warm-Up Configuration
For optimal performance when using the **Facebook Account Warm-Up** feature, a sample configuration might look like this:

- **Interaction Probability**: 60% (ensures a balance between passive browsing and active engagement)
- **Execution Interval**: 10 seconds (time between simulated interactions)
- **Session Duration**: 2 hours (total time the feature runs before needing a manual restart)

```java
setInteractionProbability(60); 
setExecutionInterval(10); // in seconds
setSessionDuration(7200); // in seconds (2 hours)
startWarmUpSession(); // Start the warm-up process
```

#### Facebook Auto-Reply Parameter Settings
To achieve a responsive customer service experience with the **Facebook Auto-Reply**, consider the following parameters:

- **Operation Interval**: 3 minutes (ideal for maintaining prompt replies)
- **Message Template**: Pre-defined replies stored in a file for consistency
- **Delete After Sending**: Enabled, to keep the inbox clean

```java
setOperationInterval(3); // Check every 3 minutes
setResponseMode(file); // Using a file with standard replies
setDeleteAfterSending(true); // Clean up after response
```

### Conclusion
MadHub revolutionizes the way users interact with social media through its powerful automation features designed for cloud phone environments. By utilizing features such as **Facebook Account Warm-Up** and **Facebook Auto-Reply**, users can enhance their social media presence, ensure engaging interactions, and maintain high levels of customer service. MadHub’s comprehensive capabilities offer flexibility and depth, making it an ideal tool for anyone seeking to streamline their social media management processes.
