import Link from 'next/link'
import { Mail, Linkedin } from 'lucide-react'
import { profile } from '@/lib/portfolio-data'

export function Sidebar() {
  return (
    <aside className="space-y-6">
      <div>
        <h1 className="text-2xl font-bold">{profile.name}</h1>
        <p className="text-muted-foreground">{profile.tagline}</p>
      </div>

      <div className="flex gap-4">
        {profile.email && (
          <a
            href={mailto:${profile.email}}
            target="_blank"
            rel="noopener noreferrer"
            className="flex items-center gap-2 text-sm hover:underline"
          >
            <Mail className="h-4 w-4" />
            <span>Email</span>
          </a>
        )}

        {profile.linkedin && (
          <a
            href={profile.linkedin}
            target="_blank"
            rel="noopener noreferrer"
            className="flex items-center gap-2 text-sm hover:underline"
          >
            <Linkedin className="h-4 w-4" />
            <span>LinkedIn</span>
          </a>
        )}
      </div>
    </aside>
  )
}
