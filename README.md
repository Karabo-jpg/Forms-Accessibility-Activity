# HTML Forms and Accessibility - Group Assignment
 
 ## 👥 Team Members
 - **Karabo:** Form Structure, Integration & Review Lead
 - **Tabitha:** Accessibility Lead  
 - **Jesse:** Validation Lead
 
 📄 **Project Document:** [View on Google Docs](https://docs.google.com/document/d/1GooSfeqiM5WtWPEwy810JZioUfCqKjCV_TSOJwx0UBc/edit?usp=sharing)
 
 ## 📋 Project Overview
 This is a collaborative group assignment where we created an accessible HTML registration form with proper validation and ARIA attributes.
 
 ## 👥 Group Roles & Responsibilities
 
 ### ✅ Role 1: Form Structure Lead (Completed)
 **Responsible for:**
 - Creating the `<form>` structure
 - Adding labels and inputs for:
   - Full Name
   - Email Address
   - Password
   - Terms & Conditions checkbox
 - Ensuring semantic HTML and proper label–input relationships
 
 **Status:** ✅ **COMPLETED**
 
 ### ✅ Role 2: Validation Lead (Completed)
 **Responsible for:**
 - Applying built-in HTML validation:
   - `required` on all fields
   - `type="email"` for email (already present)
   - `minlength` for password
   - `pattern` for password strength
 - Testing browser validation behavior
 
 **Status:** ✅ **COMPLETED**
  
 ### ✅ Role 3: Accessibility (ARIA) Lead (Completed)
 **Responsible for:**
 - Adding appropriate ARIA attributes:
   - `aria-label`
   - `aria-describedby`
   - `aria-labelledby`
 - Ensuring:
   - Password requirements are announced to screen readers
   - Checkbox has an accessible label
   - `<form>` includes `role="form"`
 - Verifying accessibility with an accessibility checker
  
 **Status:** ✅ **COMPLETED**
  
  ### ✅ Role 4: Integration & Review Lead (Completed)
 **Responsible for:**
 - Reviewing the full form for consistency
 - Ensuring all roles' work is properly integrated
 - Leading final testing and cleanup
  
 **Status:** ✅ **COMPLETED**
 
 ---
 
 ## 📝 Form Structure (Completed by Form Structure Lead)
 
 ### Current Implementation:
 
 ✅ **Semantic HTML Structure**
 - Proper `<!DOCTYPE html>` declaration
 - Language attribute: `lang="en"`
 - Responsive viewport meta tag
 - Clean, indented code structure
 
 ✅ **Form Fields with Proper Labels:**
 1. **Full Name Field**
    - `<label for="fullName">` with matching input `id="fullName"`
    - Type: `text`
    - Placeholder provided
 
 2. **Email Address Field**
    - `<label for="email">` with matching input `id="email"`
    - Type: `email` (base type set, validation pending)
    - Placeholder provided
 
 3. **Password Field**
    - `<label for="password">` with matching input `id="password"`
    - Type: `password`
    - Placeholder provided
    - Password hint already included (`id="passwordRequirements"`)
 
 4. **Terms & Conditions Checkbox**
    - `<label for="terms">` with matching input `id="terms"`
    - Type: `checkbox`
    - Clickable label with link to terms
 
 5. **Submit Button**
    - Clear call-to-action: "Register"
    - Full-width, styled appropriately
 
 ---
 
 ## 🎨 Design Features
 
 ### Professional Styling Included:
 - **Modern gradient background** (purple gradient)
 - **Clean white form container** with shadow effects
 - **Responsive design** (works on all screen sizes)
 - **Focus states** for better user experience
 - **Hover effects** on buttons
 - **Consistent spacing** and typography
 - **User-friendly interface** with clear visual hierarchy
 
 ---
 
 ## ✅ Testing Checklist (Integration & Review Lead)
 
 Once all teammates complete their roles, test:
 
 - [x] **Empty form submission** - Should show validation errors
 - [x] **Invalid email** (e.g., `abc@`) - Should show email format error  
 - [x] **Weak password** (e.g., `pass123`) - Should fail pattern validation
 - [x] **Short password** (e.g., `Pass1`) - Should fail minlength validation
 - [x] **Unchecked terms checkbox** - Should prevent submission
 - [x] **Valid submission** - All fields filled correctly
 - [x] **Screen reader announcement** - Password requirements read aloud
 - [x] **Keyboard navigation** - Tab through all fields
 - [x] **Visual consistency** - All styling is uniform
 - [x] **Cross-browser testing** - Chrome, Firefox, Edge
 
 ---
 
 ## 📂 File Structure
 
 ```
 HTML Forms and Accessibility/
 ├── index.html          ← Main form file
 └── README.md          ← This documentation file
 ```
 
 ---
 
 ## 🎯 Assignment Requirements Met
 
 ### Step 1: Create the Basic Form ✅
 - [x] Full Name (text input)
 - [x] Email Address (email input)
 - [x] Password (password input)
 - [x] Terms and Conditions (checkbox)
 - [x] Submit button
 
 ### Step 2: Add Built-in Validation ✅
  - [x] Require all fields to be filled
  - [x] Enforce valid email format
  - [x] Password minimum length (8 characters)
  - [x] Password pattern (uppercase + number)
  
  ### Step 3: Enhance with ARIA ✅
  - [x] ARIA attributes for context
  - [x] ARIA description for password requirements
  - [x] Accessible checkbox labeling
  - [x] `role="form"` on form element
  
  ### Step 4: Test the Form ✅
  - [x] Empty field submission
  - [x] Invalid email
  - [x] Weak password
  - [x] ARIA descriptions with assistive tech
 
