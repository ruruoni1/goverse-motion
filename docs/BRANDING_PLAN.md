# GOVERSE Motion: name and first release plan

## Name

- Product name: **GOVERSE Motion**
- Korean descriptor: **무료 모션 자막 제작기**
- Repository: `ruruoni1/goverse-motion`
- Short description: **SRT 자막을 시간에 맞춰 움직이는 영상으로 만드는 무료 브라우저 도구**

“Motion” names the animated output, while “GOVERSE” ties the tool to the user's existing channel brand. The Korean descriptor makes clear that this is a subtitle workflow as well as a lyric-video engine. Treat the name as a working product name until a public launch; no trademark clearance has been performed.

## Audience and promise

Korean creators who already produce subtitles in Vrew, CapCut, or another editor can bring those SRT files into a browser-based motion graphics editor without converting them first. Cue start and end times, including silent gaps, should remain aligned with the source subtitle file.

## First release

1. Import SRT and LRC files from the lyric editor.
2. Preserve SRT cue start/end times and gaps between cues.
3. Read UTF-8, UTF-16, and Korean Windows-encoded subtitle files.
4. Keep the inherited animation, preview, and video export workflows.
5. Let users export the imported cue starts as LRC when another tool needs that format; explain that LRC cannot retain SRT end times.
6. Publish the free, account-free browser app from GitHub Pages after local review.

GitHub Pages serves only the Korean edition from the repository root. The page title, description, navigation, and user-facing instructions must remain Korean; other upstream translations can remain in source modules but are not generated as Pages editions.

## Attribution and source lineage

This project is based on [852wa/JIZURA](https://github.com/852wa/JIZURA), licensed under MIT. Preserve the upstream `LICENSE` and `THIRD_PARTY_NOTICES.md`; identify the fork in public project documentation. The output rights for users' own media do not change the copyright in lyrics, music, fonts, or other assets they provide.

## Current status

The GitHub fork exists. The local app shell, direct SRT import, cue-time preservation, and LRC conversion path are implemented on the working branch; generated browser editions are up to date. GitHub Pages has not been enabled and no public release has been made.
