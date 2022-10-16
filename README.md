⋊> ~/w/r/e/test-yarn3-duplicates on master ⨯ yarn why react-draggable -R                            
└─ test-yarn3-duplicates@workspace:.
   └─ react-grid-layout@npm:1.3.4 [8f25d] (via npm:^1.3.4 [8f25d])
      ├─ react-draggable@npm:4.4.5 [6c42a] (via npm:^4.0.0 [6c42a])
      └─ react-resizable@npm:3.0.4 [6c42a] (via npm:^3.0.4 [6c42a])
         └─ react-draggable@npm:4.4.5 [5d025] (via npm:^4.0.3 [5d025])
⋊> ~/w/r/e/test-yarn3-duplicates on master ⨯ yarn info -AR --virtuals react-draggable
├─ react-draggable@npm:4.4.5
│  ├─ Instances: 2
│  ├─ Version: 4.4.5
│  │
│  └─ Dependencies
│     ├─ clsx@npm:^1.1.1 → npm:1.2.1
│     └─ prop-types@npm:^15.8.1 → npm:15.8.1
│
├─ react-draggable@npm:4.4.5 [5d025]
│  ├─ Version: 4.4.5
│  │
│  └─ Peer dependencies
│     ├─ @types/react-dom@* → ✘
│     ├─ @types/react@* → ✘
│     ├─ react-dom@>= 16.3.0 → ✘
│     └─ react@>= 16.3.0 → npm:17.0.2
│
└─ react-draggable@npm:4.4.5 [6c42a]
   ├─ Version: 4.4.5
   │
   └─ Peer dependencies
      ├─ @types/react-dom@* → ✘
      ├─ @types/react@* → ✘
      ├─ react-dom@>= 16.3.0 → npm:17.0.2 [8f25d]
      └─ react@>= 16.3.0 → npm:17.0.2
