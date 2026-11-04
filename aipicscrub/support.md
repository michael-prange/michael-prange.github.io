---
title: AI PicScrub Support
---

# AI PicScrub Support

AI PicScrub removes AI-provenance metadata (C2PA Content Credentials, IPTC Digital Source Type tags and AI generator names) from your photos, without changing the image itself. It doesn't remove invisible watermarks that some AI tools put in the image.

## Frequently asked questions

**Why does Instagram say "AI info" on my photo?**  
Instagram and Facebook read AI tags that editing tools write into the photo file, even for small edits. [Read why your photo was labeled and how to remove the tag →](ai-info-label.md)

**Does it change my photo's quality?**  
No. The image data is copied exactly as it is; only the AI-related metadata is removed.

**Are my original photos changed?**  
No. AI PicScrub makes cleaned copies. Your originals stay in your library untouched.

**Which formats are supported?**  
JPEG, HEIC and PNG. Photos in other formats that contain no AI metadata are shared or saved unchanged.

**Why does a photo show an error?**  
AI PicScrub checks every cleaned copy before offering it. If an AI tag is stored somewhere it can't remove, you'll see an error instead of a copy that's still tagged.

**Does it remove invisible watermarks?**  
No. AI PicScrub removes metadata only. Watermarks that are part of the image's pixels, like Google's SynthID, stay in the cleaned copy.

**What does a watermark notice on a photo mean?**  
AI PicScrub found signs of an invisible watermark that it won't remove. The notice says how it was found:

- **Found in the image:** the pixels carry the open watermark that Stable Diffusion adds. It's usually only detectable in an unedited PNG from the generator.
- **Declared in the metadata:** the photo's Content Credentials or other metadata say a watermark was added.
- **Usually added by this AI tool:** the metadata names a tool, such as Google Gemini or Meta AI, that watermarks the images it makes.

Most watermarks can't be detected on your device, so a photo may have one even when no notice appears.

## Terms of use

By using AI PicScrub, you agree to these terms, which add to [Apple's Standard License Agreement](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/):

- Only clean photos that you own or have permission to modify.
- Removing AI tags doesn't change how an image was made. Follow the laws and platform rules where you share it, including any that require you to disclose AI-generated or AI-edited content.
- Don't use AI PicScrub to remove authorship or copyright information from other people's work, or to infringe their rights.
- Don't use AI PicScrub to deceive, defraud, impersonate or harass anyone.
- AI PicScrub is provided as is, without warranty. To the extent the law allows, the developer isn't liable for how you use the app or the images it produces.

## Contact

Email: prange@alum.mit.edu
