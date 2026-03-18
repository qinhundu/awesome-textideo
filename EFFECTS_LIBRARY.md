# Textideo Effects Library

Complete reference for all video and image effects available in Textideo.

---

## 🎬 Video Effects

### Camera Movements

#### 1. Dolly Zoom (Vertigo Effect)
**Description**: Camera moves in one direction while zooming in opposite direction

**Parameters**:
- Speed: Slow (10s) / Medium (5s) / Fast (2s)
- Intensity: Subtle / Moderate / Dramatic
- Direction: In-Out / Out-In

**Best For**:
- Dramatic reveals
- Psychological tension
- Surreal moments

**Example Prompt**:
```yaml
Subject: Person in hallway
Camera: Dolly zoom
Speed: 5 seconds
Intensity: Moderate
Mood: Unsettling, dramatic
```

---

#### 2. Orbit
**Description**: Circular camera movement around subject

**Parameters**:
- Angle: 90° / 180° / 270° / 360°
- Speed: Slow / Medium / Fast
- Height: Low / Eye-level / High
- Direction: Clockwise / Counter-clockwise

**Best For**:
- Product showcases
- 360° views
- Character reveals

**Example Prompt**:
```yaml
Subject: Product on pedestal
Camera: 360° orbit
Speed: Slow (10s)
Height: Eye-level
Direction: Clockwise
```

---

#### 3. Crane/Jib
**Description**: Vertical camera movement up or down

**Parameters**:
- Direction: Up / Down
- Range: Low / Medium / High
- Speed: Slow / Medium / Fast

**Best For**:
- Epic establishing shots
- Reveals
- Scene transitions

**Example Prompt**:
```yaml
Subject: City street
Camera: Crane up
Range: Full building height
Speed: Slow
Mood: Epic, grand
```

---

#### 4. Tracking Shot
**Description**: Camera follows subject movement

**Parameters**:
- Direction: Forward / Backward / Lateral
- Distance: Close / Medium / Far
- Stabilization: Handheld / Steadicam / Locked-off

**Best For**:
- Following action
- Walkthroughs
- Continuous shots

**Example Prompt**:
```yaml
Subject: Person walking
Camera: Forward tracking
Distance: 2 meters
Stabilization: Steadicam
Mood: Smooth, professional
```

---

#### 5. Drone/Aerial
**Description**: Aerial perspective from above

**Parameters**:
- Altitude: Low / Medium / High
- Movement: Static / Forward / Orbit / Reveal
- Angle: Top-down / 45° / Horizon

**Best For**:
- Real estate
- Landscapes
- Event coverage

**Example Prompt**:
```yaml
Subject: Beach resort
Camera: Drone aerial
Movement: Forward approach
Altitude: 100 meters
Angle: 45° downward
```

---

### Visual Effects

#### 1. Slow Motion
**Description**: Reduced playback speed

**Speed Options**:
- 60fps → 50% slow (30fps playback)
- 120fps → 25% slow (30fps playback)
- 240fps → 12.5% slow (30fps playback)

**Best For**:
- Action sequences
- Emotional moments
- Detail emphasis

**Example Prompt**:
```yaml
Action: Water balloon popping
Speed: 25% (240fps)
Focus: Capture every droplet
Mood: Dramatic, detailed
```

---

#### 2. Time Lapse
**Description**: Accelerated time passage

**Speed Options**:
- 2x / 5x / 10x / 30x / 60x acceleration

**Best For**:
- Sunsets/sunrises
- Cloud movement
- Crowds/traffic
- Construction

**Example Prompt**:
```yaml
Subject: City skyline
Time: Sunset to night
Speed: 30x acceleration
Duration: 15 seconds final
Elements: Clouds moving, lights appearing
```

---

#### 3. Motion Blur
**Description**: Simulated fast movement blur

**Parameters**:
- Intensity: Low / Medium / High
- Direction: Horizontal / Vertical / Radial / Custom
- Shutter: 180° / 90° / 45°

**Best For**:
- Action scenes
- Speed emphasis
- Smooth transitions

**Example Prompt**:
```yaml
Subject: Racing car
Effect: Motion blur
Intensity: High
Direction: Horizontal
Shutter: 90°
Mood: Fast, dynamic
```

---

#### 4. Depth of Field
**Description**: Selective focus with background blur

**Parameters**:
- Aperture: f/1.4 / f/2.8 / f/5.6 / f/11
- Focus Point: Near / Middle / Far
- Blur Type: Gaussian / Optical / Anamorphic

**Best For**:
- Portraits
- Product focus
- Cinematic look

**Example Prompt**:
```yaml
Subject: Person portrait
Aperture: f/2.8
Focus: Eyes
Background: Soft bokeh
Mood: Professional, intimate
```

---

#### 5. Particle Effects
**Description**: Animated particles overlay

**Types**:
- ✨ Sparkles
- ❄️ Snow
- 🌸 Petals
- 💫 Dust motes
- 🔥 Embers
- 🌟 Light particles

**Parameters**:
- Density: Sparse / Medium / Dense
- Speed: Slow / Medium / Fast
- Direction: Up / Down / Swirl / Random

**Example Prompt**:
```yaml
Subject: Fantasy wizard
Particles: Magical sparkles
Density: Medium
Speed: Slow swirl
Color: Blue and white
Mood: Magical, mystical
```

---

#### 6. Light Leaks
**Description**: Film-style light flares

**Types**:
- Warm (orange/red)
- Cool (blue/purple)
- Rainbow spectrum
- Subtle / Intense

**Best For**:
- Vintage look
- Transitions
- Dreamy atmosphere

**Example Prompt**:
```yaml
Subject: Portrait
Light Leaks: Warm orange
Intensity: Subtle
Position: Top right corner
Mood: Nostalgic, warm
```

---

#### 7. Lens Flare
**Description**: Light reflection in lens

**Types**:
- Anamorphic (horizontal streaks)
- Circular (bokeh rings)
- Starburst (ray pattern)
- Custom (movie-style)

**Best For**:
- Cinematic shots
- Sun/bright light sources
- Sci-fi scenes

**Example Prompt**:
```yaml
Subject: Outdoor scene
Light Source: Sun in frame
Flare Type: Anamorphic
Intensity: Moderate
Mood: Cinematic, epic
```

---

#### 8. Color Grading
**Description**: Professional color correction

**Presets**:
- 🎬 Cinematic (teal & orange)
- 🌅 Warm (golden hour)
- ❄️ Cool (blue tones)
- 🎨 Vintage (faded)
- 🌈 Vibrant (saturated)
- 🖤 B&W (monochrome)

**Parameters**:
- Temperature: Cool / Neutral / Warm
- Tint: Green / Neutral / Magenta
- Contrast: Low / Medium / High
- Saturation: Muted / Natural / Vibrant

**Example Prompt**:
```yaml
Subject: Travel vlog
Color Grade: Warm golden hour
Temperature: Warm
Contrast: Medium
Saturation: Natural
Mood: Inviting, happy
```

---

### Transitions

#### 1. Cut
**Description**: Instant scene change

**Best For**: Fast-paced content, action sequences

---

#### 2. Fade
**Description**: Gradual appearance/disappearance

**Types**:
- Fade In (from black)
- Fade Out (to black)
- Fade to White
- Fade to Color

**Best For**: Scene changes, beginnings/endings

---

#### 3. Dissolve
**Description**: Overlapping transition

**Duration**: 0.5s / 1s / 2s / 3s

**Best For**: Time passage, emotional connections

---

#### 4. Wipe
**Description**: Line moves across screen

**Directions**: Left/Right/Up/Down/Diagonal

**Best For**: Dynamic transitions, location changes

---

#### 5. Zoom Transition
**Description**: Zoom into/out of scene

**Types**:
- Zoom In → Cut
- Zoom Out → Cut
- Whip Zoom

**Best For**: Energy, focus changes

---

## 🖼️ Image Effects

### Artistic Styles

#### 1. Oil Painting
**Description**: Classical painted appearance

**Parameters**:
- Brush Size: Fine / Medium / Bold
- Texture: Smooth / Impasto
- Detail: Low / Medium / High

**Best For**: Artistic portraits, landscapes

---

#### 2. Watercolor
**Description**: Soft, flowing watercolor look

**Parameters**:
- Wetness: Dry / Medium / Wet
- Bleed: Low / Medium / High
- Paper Texture: Smooth / Rough

**Best For**: Gentle, artistic images

---

#### 3. Pencil Sketch
**Description**: Hand-drawn pencil appearance

**Types**:
- HB Pencil (light)
- 2B-4B Pencil (medium)
- 6B+ Pencil (dark, bold)

**Best For**: Artistic portraits, architectural drawings

---

#### 4. Pop Art
**Description**: Bold Warhol-style colors

**Parameters**:
- Colors: 2-color / 4-color / Full
- Contrast: High / Extreme
- Dots: Halftone pattern on/off

**Best For**: Bold, creative statements

---

#### 5. Anime/Manga
**Description**: Japanese animation style

**Parameters**:
- Eye Size: Natural / Large / Extra Large
- Line Art: Thin / Medium / Bold
- Coloring: Cel-shaded / Soft / Vibrant

**Best For**: Character art, profile pictures

---

#### 6. Pixel Art
**Description**: Retro 8-bit/16-bit style

**Resolution**: 8-bit / 16-bit / 32-bit
**Palette**: Limited (16 colors) / Extended (256 colors)

**Best For**: Gaming content, nostalgic designs

---

### Enhancement Effects

#### 1. AI Upscale
**Description**: Increase resolution with AI

**Options**:
- 2x Upscale (e.g., 1080p → 4K)
- 4x Upscale (e.g., 720p → 4K)
- 8x Upscale (e.g., 480p → 4K)

**Best For**: Old photos, small images, print preparation

---

#### 2. Denoise
**Description**: Remove grain and noise

**Strength**: Light / Medium / Strong / Extreme

**Best For**: Low-light photos, old images

---

#### 3. Sharpen
**Description**: Enhance edge definition

**Amount**: Subtle / Medium / Strong / Extreme
**Radius**: 0.5px / 1px / 2px

**Best For**: Soft images, detail enhancement

---

#### 4. HDR
**Description**: High dynamic range

**Tone Mapping**: Natural / Balanced / Dramatic / Surreal

**Best For**: Landscapes, architecture, high-contrast scenes

---

### Creative Effects

#### 1. Double Exposure
**Description**: Blend two images together

**Blend Modes**: Screen / Multiply / Overlay / Soft Light

**Best For**: Artistic portraits, conceptual art

---

#### 2. Duotone
**Description**: Two-color scheme

**Presets**:
- Classic (Black + One color)
- Modern (Two vibrant colors)
- Custom (User-selected)

**Best For**: Modern designs, branded content

---

#### 3. Color Splash
**Description**: B&W with selective color

**Selection**: Auto-detect / Manual brush / Color range

**Best For**: Dramatic, focused attention

---

#### 4. Bokeh
**Description**: Beautiful background blur

**Shapes**: Circular / Hexagonal / Heart / Star
**Size**: Small / Medium / Large
**Intensity**: Subtle / Medium / Strong

**Best For**: Portraits, romantic scenes

---

#### 5. Tilt-Shift
**Description**: Miniature effect

**Focus Area**: Top / Middle / Bottom / Custom
**Blur Amount**: Light / Medium / Strong

**Best For**: Creative perspectives, model-like scenes

---

## 🎯 Quick Reference

### Most Popular Video Effects
1. Orbit (Product videos)
2. Slow Motion (Action)
3. Dolly Zoom (Drama)
4. Color Grading (All videos)
5. Drone Aerial (Real estate)

### Most Popular Image Effects
1. Style Transfer (Artistic)
2. HDR Enhancement (Landscapes)
3. Background Removal (Products)
4. Bokeh (Portraits)
5. Vintage Film (Social media)

---

## 💡 Pro Tips

### Video Effects
- Combine orbit + slow motion for dramatic product reveals
- Use dolly zoom sparingly for maximum impact
- Match color grading to your brand palette
- Layer multiple subtle effects for professional results

### Image Effects
- Start with enhancement before artistic effects
- Use HDR subtly for natural-looking results
- Combine style transfer with texture overlays
- Save custom presets for consistent branding

---

*Last updated: March 2026*
