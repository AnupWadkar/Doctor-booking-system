# श्री विश्वरूप आयुर्वेदिक चिकित्सालय - Appointment Booking System

## 🌿 About
Simple and user-friendly appointment booking system for Ayurvedic clinic with bilingual support (English & Marathi).

### Features
- ✅ Patient booking without login
- ✅ 30-minute appointment slots
- ✅ Morning & Evening sessions
- ✅ Admin panel for appointment management
- ✅ Bilingual: English & Marathi
- ✅ Mobile responsive
- ✅ Download patient list as CSV
- ✅ Block dates for holidays

### Doctor Information
**Dr. Santosh Gambhire - MD (Ayu.)**
- 📍 Maharaja Vihar, Madhav Nagar, Mosman Road, Akola
- 📧 shrivishwarup@gmail.com
- 📱 9511784298

## 🚀 Deploy to Vercel

### Method 1: Using Vercel CLI (Recommended)

1. **Install Vercel CLI** (if not already installed):
   ```bash
   npm install -g vercel
   ```

2. **Login to Vercel**:
   ```bash
   vercel login
   ```

3. **Deploy**:
   ```bash
   vercel
   ```
   - Follow the prompts
   - Press Enter to accept defaults
   - Your site will be deployed!

4. **Deploy to Production**:
   ```bash
   vercel --prod
   ```

### Method 2: Using Vercel Dashboard

1. Go to [vercel.com](https://vercel.com)
2. Sign up or login with GitHub/GitLab/Bitbucket
3. Click "Add New Project"
4. Upload this folder or connect your Git repository
5. Click "Deploy"

### Method 3: Deploy from GitHub

1. Create a new GitHub repository
2. Upload all files from this folder
3. Go to [vercel.com](https://vercel.com)
4. Import your GitHub repository
5. Click "Deploy"

## 🔐 Admin Access

**Default Admin Credentials:**
- Username: `admin`
- Password: `admin123`

⚠️ **Important:** Change these credentials in production by modifying the login validation in the code.

## 📱 Usage

### For Patients:
1. Open the website
2. Select preferred date
3. Choose available time slot
4. Fill in details
5. Submit booking request

### For Admin:
1. Click "Admin Login" / "प्रशासक लॉगिन"
2. Enter credentials
3. View and manage appointments
4. Approve/Complete/Cancel bookings
5. Download patient list
6. Block dates for holidays

## 🌐 After Deployment

Your appointment system will be live at:
- `https://your-project-name.vercel.app`

You can share this URL with your patients!

## 💾 Data Storage

- Uses browser localStorage (client-side)
- Data persists on the user's device
- No server/database required
- Free to host and run

## 🎨 Customization

To customize clinic timings, slot duration, or other settings, edit the `index.html` file:
- Line ~640: Clinic timings in HTML
- Line ~210: Slot generation function
- Line ~55-70: Color scheme in CSS variables

## 📞 Support

For technical support or customization:
- Email: shrivishwarup@gmail.com
- Mobile: 9511784298

---

Made with ❤️ for श्री विश्वरूप आयुर्वेदिक चिकित्सालय
