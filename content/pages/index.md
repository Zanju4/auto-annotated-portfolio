---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: >-
      IT Support & Junior Network Specialist
    subtitle: >-
      Experienced in supporting enterprise environments with 300+ users. Expertise in Microsoft 365, Active Directory, Windows administration, and foundational networking. Focused on system reliability, security, and efficient troubleshooting.
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
      flexDirection: row-reverse
      textAlign: left
    type: HeroSection
    actions: []
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions: []
    subtitle:
      type: FeaturedItemsLayout
      elementId: ''
      showImage: false
      showDescription: true
      showSubtitle: true
      showTitle: true
      actions: []
      items:
        - title: Linux Print Server (CUPS)
          subtitle: Linux, CUPS, Networking
          text: >-
            Configured a Linux-based print server using CUPS to support multiple users and virtual PDF printers. Implemented printer management, permissions, and client testing.
          type: FeaturedItem
          styles:
            self:
              textAlign: left
        - title: File Sharing Server (Samba & FTP)
          subtitle: Linux, Samba, FTP, User Management
          text: >-
            Implemented secure file-sharing services using Samba and FTP for cross-platform environments. Managed user access controls and directory permissions.
          type: FeaturedItem
          styles:
            self:
              textAlign: left
        - title: Email Server Deployment
          subtitle: Linux, Postfix, Dovecot, Roundcube
          text: >-
            Deployed and configured a functional email server with Postfix and Dovecot, including webmail access. Implemented user authentication and mail routing.
          type: FeaturedItem
          styles:
            self:
              textAlign: left
---
