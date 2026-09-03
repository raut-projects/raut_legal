# RAUT - Play Store Data Safety Section

**For Google Play Console → Data Safety Form**

---

## Data Collection Summary

### Does your app collect or share any of the required user data types?
**YES**

---

## Data Types Collected

### 1. LOCATION (Precise & Approximate)
**Collected:** YES  
**Shared:** YES (with drivers/riders during rides)  
**Required:** YES  
**Purpose:**
- App functionality (ride matching, navigation)
- Fraud prevention & security

**Details:**
- **Riders:** Location when booking ride, pickup/dropoff addresses
- **Drivers:** Continuous background location when online to show live position
- **Shared with:** Other users (drivers see rider pickup, riders see driver location)

---

### 2. PERSONAL INFO

#### Name
**Collected:** YES  
**Shared:** YES (with ride participants)  
**Required:** YES  
**Purpose:** App functionality (show to driver/rider during ride)

#### Email Address
**Collected:** NO (Optional, not required)  
**Shared:** NO  
**Required:** NO  
**Purpose:** Account management (if provided)

#### User IDs
**Collected:** YES  
**Shared:** NO  
**Required:** YES  
**Purpose:** App functionality, analytics, fraud prevention

#### Phone Number
**Collected:** YES  
**Shared:** YES (temporarily with ride participants)  
**Required:** YES  
**Purpose:** Account creation, authentication, ride coordination

---

### 3. PHOTOS
**Collected:** YES  
**Shared:** YES (with ride participants)  
**Required:** NO (Optional)  
**Purpose:** App functionality (profile pictures)

**Details:**
- Profile photos optional
- Shown to drivers/riders during rides
- Drivers must provide vehicle photos (required)

---

### 4. FINANCIAL INFO

#### Payment Info
**Collected:** YES  
**Shared:** YES (with payment processors)  
**Required:** YES  
**Purpose:** Payment processing

**Details:**
- Mobile money phone numbers
- Cash payment confirmations
- Transaction history

#### Purchase History
**Collected:** YES  
**Shared:** NO  
**Required:** YES  
**Purpose:** App functionality (ride history)

---

### 5. MESSAGES

#### Other in-app messages
**Collected:** YES  
**Shared:** YES (with support team, ride participants)  
**Required:** NO  
**Purpose:** App functionality (support, feedback)

---

### 6. APP ACTIVITY

#### App interactions
**Collected:** YES  
**Shared:** NO  
**Required:** NO  
**Purpose:** Analytics, app performance

**Details:**
- Search queries
- Ride requests
- Button clicks
- Feature usage

---

### 7. APP INFO & PERFORMANCE

#### Crash logs
**Collected:** YES  
**Shared:** NO  
**Required:** NO  
**Purpose:** App performance, bug fixes

#### Diagnostics
**Collected:** YES  
**Shared:** NO  
**Required:** NO  
**Purpose:** App performance

---

### 8. DEVICE OR OTHER IDs

#### Device ID
**Collected:** YES  
**Shared:** NO  
**Required:** YES  
**Purpose:**
- App functionality
- Fraud prevention
- Analytics

---

## Data Security

### Is all user data encrypted in transit?
**YES** - All data transmitted over HTTPS/TLS 1.3

### Do you provide a way for users to request that their data be deleted?
**YES** - Users can request deletion via:
- In-app: Settings → Account → Delete Account
- Email: privacy@raut.co.tz

---

## Data Usage & Handling

### For each data type, select all that apply:

**Location (Precise):**
- ✅ Used for app functionality
- ✅ Can be made optional (riders only - drivers must enable for online status)
- ✅ Used for fraud prevention, security, and compliance
- ✅ Transferred using encryption
- ✅ User can request deletion

**Personal Info (Name, Phone):**
- ✅ Used for app functionality
- ✅ Required (cannot be optional)
- ✅ Used for fraud prevention, security, and compliance
- ✅ Transferred using encryption
- ✅ User can request deletion

**Photos:**
- ✅ Used for app functionality
- ✅ Can be made optional
- ✅ Transferred using encryption
- ✅ User can request deletion

**Financial Info:**
- ✅ Used for app functionality
- ✅ Required (cannot be optional)
- ✅ Used for fraud prevention, security, and compliance
- ✅ Transferred using encryption
- ✅ User can request deletion

**App Activity:**
- ✅ Used for analytics
- ✅ Can be made optional
- ✅ Transferred using encryption
- ✅ User can request deletion

---

## Privacy Policy

**Privacy Policy URL:**  
[Will be: https://raut.co.tz/privacy or hosted on GitHub Pages]

---

## Notes for Play Console

### Data Shared With
- **Other Users:** Location, name, photo, phone (during active rides only)
- **Service Providers:** Payment processors, mapping services, SMS gateway
- **For Legal Reasons:** Law enforcement when required

### Data NOT Collected
- ❌ Email (optional only)
- ❌ Address (only addresses for rides, not permanent address)
- ❌ User content (no chat/social features)
- ❌ Web browsing history
- ❌ Calendar
- ❌ Contacts

### Special Permissions Justification

**Location (Background - Drivers Only):**
- **Purpose:** Show live driver position to nearby riders
- **Why Background:** Driver needs to appear available even when app minimized
- **Alternative:** Not feasible - drivers must be visible to accept rides

**Location (While Using - Riders):**
- **Purpose:** Set pickup location, match with nearby drivers
- **Why Required:** Cannot book ride without location

**Camera:**
- **Purpose:** Upload profile photo, driver uploads vehicle photos
- **Alternative:** Photos optional for riders, gallery upload available

---

## Compliance Notes

### Google Play Policy
✅ Compliant with:
- Google Play Developer Policy
- User Data Policy
- Permissions Policy
- Families Policy (N/A - app is 18+)

### Special Declarations
- ✅ App does not target children under 13
- ✅ Privacy policy provided
- ✅ Data safety form completed accurately
- ✅ Prominent disclosure of location usage
- ✅ No deceptive behavior
- ✅ No malware or harmful behavior

---

## App Content Rating

**IARC Questionnaire Answers:**

**Violence:**
- No depictions of violence

**Sexual Content:**
- No sexual content

**Language:**
- No profanity

**Controlled Substances:**
- No references to drugs/alcohol

**Gambling:**
- No gambling features

**In-App Purchases:**
- No (payments are for services, not purchases)

**User-Generated Content:**
- Yes - users can submit ratings/reviews
- Moderated by RAUT team

**Shares User Location:**
- Yes - shared with drivers during rides

**Expected Rating:** PEGI 3, ESRB Everyone, USK 0, etc. (or Teen due to ride-sharing context)

---

## Marketing Copy for Data Safety

**What We Collect:**
We collect your location, name, and phone number to connect you with drivers and provide ride services. Payment information is collected to process fares.

**How We Use It:**
Your data is used to match you with nearby drivers, calculate fares, and ensure safe transportation. Location is shared with your driver during active rides only.

**Your Control:**
You can delete your account and data anytime. We only collect what's necessary to provide our services.

**Security:**
All data is encrypted in transit and at rest. We follow industry-standard security practices.
