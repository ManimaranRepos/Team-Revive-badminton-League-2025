# Team-Revive-badminton-League-2025
Team Revive, an NGO at Olympia Opaline, Chennai, organizes monthly food drives for the homeless and supports flood relief. They also host community events like dance and sports. This year’s badminton tournament at Ultimate Sports, Navalur, saw 10 teams compete in a round-robin format, where we reached the semifinals and finals.

# Team Revive — Badminton Tournament Media

**About Team Revive**  
Team Revive (Olympia Opaline, Chennai) runs monthly food drives for people living on the streets, supports flood relief, and organizes community events (dance, games, sports).

**This year**  
We participated in the annual badminton tournament at Ultimate Sports, Navalur. Ten teams played a round-robin; our team progressed to the semifinals and finals.

**What this repo contains**  
- Photos and videos from the tournament (organized by team/match).  
- Lightweight gallery pages so anyone can open the URL and view media.

**Purpose / Tech goals**  
As a .NET developer, I’m using this repo as a fun demo to:
- Host media publicly and efficiently (S3 + CloudFront).
- Use serverless processing (AWS Lambda) for image/video resizing, thumbnails, and metadata extraction.
- Serve a small static frontend (GitHub Pages or S3 static site) with signed URLs for selective access.
- Optionally add a .NET Core backend to handle uploads and trigger Lambda processing.

**How to view**  
Open the `gallery/` folder or the site at `<your-site-url>` (replace with your GitHub Pages or CloudFront URL).

**Contributing / Notes**  
- Add media under `media/<team-name>/` with a short `metadata.json` per match.  
- I’ll include processing Lambdas and a sample .NET uploader in the `infra/` and `src/` folders.

