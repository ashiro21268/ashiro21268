<div id="smart-link"></div>
<script src="https://unpkg.com/react@18/umd/react.production.min.js"></script>
<script src="https://unpkg.com/react-dom@18/umd/react-dom.production.min.js"></script>
<script src="https://cdn.tailwindcss.com"></script>
<script src="https://unpkg.com/lucide-react@latest"></script>

<script>
  // Initialize with your configuration
  const smartLinkConfig = {
    password: 'your-secure-password', // Change this!
    profile: {
      name: 'Your Name',
      bio: 'Your Bio',
      avatar: 'your-avatar-url'
    },
    links: [
      { id: 1, title: 'Portfolio', url: 'https://your-site.com', icon: 'globe' }
      // Add more links here
    ]
  };

  // Initialize SmartLink
  const container = document.getElementById('smart-link');
  ReactDOM.createRoot(container).render(React.createElement(SmartLink, smartLinkConfig));
</script>
