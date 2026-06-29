# project-slide-demo

## MLOps Observability Demo - Model Foundry

A professional 2-slide HTML presentation about Model Foundry, an internal MLOps observability platform at LinkedIn.

### Quick Start

#### Option 1: Open in Browser (Recommended)
1. Open `mlops-observability-demo.html` in your web browser
2. Navigate using:
   - **Arrow keys** (← →)
   - **Navigation buttons** (Previous/Next)
   - **Dot indicators** (click to jump to slide)

#### Option 2: Start a Local Server
```bash
# Navigate to the project directory
cd /Users/khanhdao/Works/project-slide-demo

# Start a simple HTTP server
python3 -m http.server 8000

# Open in browser
open http://localhost:8000/mlops-observability-demo.html
```

### Files

- **mlops-observability-demo.html** - Main slide presentation
- **featuredrift.mp4** - Demo video (optional - embed in slide)

### Adding Your Video

The slide includes a video section on slide 2. To add your video:

1. **For local video (MP4):**
   - Place the video file in the project directory
   - Open `mlops-observability-demo.html`
   - Find the video placeholder section (around line 269)
   - Replace with:
   ```html
   <video controls>
       <source src="featuredrift.mp4" type="video/mp4">
       Your browser does not support the video tag.
   </video>
   ```

2. **For YouTube/Vimeo:**
   - Replace the placeholder with an iframe embed code

### Slide Contents

**Slide 1:** Title slide - Model Foundry MLOps Observability Platform

**Slide 2:** Metrics & Impact
- Core metrics built (Activity, Latency, Feature Health, Dataset Freshness, Compliance)
- Key outcomes (performance improvements, ownership clarity)
- Video embed area

### Features

✅ Responsive design  
✅ Keyboard navigation (arrow keys)  
✅ Mouse navigation (buttons & dots)  
✅ Smooth animations  
✅ Video integration ready  

### Browser Compatibility

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
