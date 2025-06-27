9<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>FireGate Lions Tree</title>
  <style>
    body {
      margin: 0;
      font-family: 'Orbitron', sans-serif;
      background: linear-gradient(to bottom, #000000, #1a1a1a);
      color: #ffd700;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      overflow: hidden;
    }
    h1 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }
    .video-container {
      width: 90%;
      max-width: 720px;
      border: 2px solid #ffd700;
      border-radius: 12px;
      overflow: hidden;
    }
    .audio-hidden {
      display: none;
    }
  </style>
</head>
<body>
  <h1>🦁 FireGate Access Granted</h1>
  <div class="video-container">
    <video width="100%" controls autoplay muted loop>
      <source src="./video/lion_firegate_trees.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
  <audio class="audio-hidden" autoplay loop>
    <source src="./public/audio/blessing_whisper_locked.mp3" type="audio/mp3">
    Your browser does not support the audio element.
  </audio>
</body>
</html>2025-06-25T10:00:19.9645608Z Current runner version: '2.325.0'
Operating System
Ubuntu
24.04.2
LTS
Runner Image
Image: ubuntu-24.04
Version: 20250615.1.0
Included Software: https://github.com/actions/runner-images/blob/ubuntu24/20250615.1/images/ubuntu/Ubuntu2404-Readme.md
Image Release: https://github.com/actions/runner-images/releases/tag/ubuntu24%2F20250615.1
Runner Image Provisioner
GITHUB_TOKEN Permissions
Actions: write
Attestations: write
Checks: write
Contents: write
Deployments: write
Discussions: write
Issues: write
Metadata: read
Models: read
Packages: write
Pages: write
PullRequests: write
RepositoryProjects: write
SecurityEvents: write
Statuses: write
Secret source: Actions
Prepare workflow directory
Prepare all required actions
Getting action download info
Download immutable action package 'actions/checkout@4.2.2'
Download immutable action package 'docker/login-action@3.4.0'
Version: 3.4.0
Digest: sha256:864ebd28db095e1602e6ef999f46a4f575083ea874918fbccf0994c2a7680450
Source commit SHA: 74a5d142397b4f367a81961eba4e8cd7edddf772
Download immutable action package 'docker/setup-buildx-action@3.11.1'
Download immutable action package 'docker/build-push-action@6.18.0'
Version: 6.18.0
Digest: sha256:a3b92a97ce4209aaf6f58880cd313602c01f9eb223c830701b91d5bbff15c4f7
Source commit SHA: 263435318d21b8e681c14492fe198d362a7d2c83
Download action repository 'aquasecurity/trivy-action@0.31.0' (SHA:76071ef0d7ec797419534a183b498b4d6366cf37)
Download action repository 'peter-evans/find-comment@v3.1.0' (SHA:3eae4d37986fb5a8592848f6a574fdf654e61f9e)
Download action repository 'peter-evans/create-or-update-comment@v4.0.0' (SHA:71345be0265236311c031f5c7866368bd1eff043)
Getting action download info
Download action repository 'aquasecurity/setup-trivy@ff1b8b060f23b650436d419b5e13f67f5d4c3087' (SHA:ff1b8b060f23b650436d419b5e13f67f5d4c3087)
Download immutable action package 'actions/cache@v4'
Version: 4.2.3
Digest: sha256:c8a3bb963e1f1826d8fcc8d1354f0dd29d8ac1db1d4f6f20247055ae11b81ed9
Source commit SHA: 5a3ec84eff668545956fd18022155c47e93e2684
Getting action download info
Download immutable action package 'actions/checkout@v4'
Version: 4.2.2
Digest: sha256:ccb2698953eaebd21c7bf6268a94f9c26518a7e38e27e0b83c1fe1ad049819b1
Source commit SHA: 11bd71901bbe5b1630ceea73d27597364c9af683
Complete job name: build