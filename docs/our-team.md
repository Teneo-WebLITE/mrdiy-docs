<script setup>
import { VPTeamMembers } from 'vitepress/theme'

const members = [
  {
    avatar: 'https://yeeqiang.me/avatar.jpeg',
    name: 'Yap Yee Qiang',
    title: 'Frontend',
    links: [
      { icon: 'github', link: 'https://github.com/yapyeeqiang' },
      { icon: 'twitter', link: 'https://twitter.com/yapyeeqiang' }
    ]
  },
]
</script>

# Our Team

Say hello to our awesome team.

<VPTeamMembers size="small" :members="members" />
