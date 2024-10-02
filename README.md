
	/* background colors */
	--bg-0: #24273a; /* main background color. */
	--bg-1: #1e2030; /* background color for secondary elements like code blocks, embeds, etc. */
	--bg-2: #363a4f; /* color of neutral buttons. */
	--bg-3: #494d64; /* color of neutral buttons when hovered. */

	/* state modifiers */
	--hover: color-mix(in oklch, var(--txt-3), transparent 80%); /* color of hovered elements. */
	--active: color-mix(in oklch, var(--txt-3), transparent 60%); /* color of elements when clicked. */
	--selected: var(--active); /* color of selected elements. */

	/* text colors */
	--txt-dark: var(--bg-0); /* color of dark text on colored backgrounds. */
	--txt-link: var(--cyan); /* color of links. */
	--txt-0: #eaeefa; /* color of bright/white text. */
	--txt-1: #cad3f5; /* main text color. */
	--txt-2: #939ab7; /* color of secondary text like channel list. */
	--txt-3: #5b6078; /* color of muted text. */

	/* accent colors */
	--acc-0: var(--lavender); /* main accent color. */
	--acc-1: var(--lavender-1); /* color of accent buttons when hovered. */
	--acc-2: var(--lavender-2); /* color of accent buttons when clicked. */

	/* borders */
	--border-width: 2px; /* panel border thickness. */
	--border-color: var(--bg-2); /* panel border color. */
	--border-hover-color: var(--acc-0); /* panel border color when hovered. */
	--border-transition: 0.2s ease; /* panel border transition. */

	/* status dot colors */
	--online-dot: var(--cyan); /* color of online dot. */
	--dnd-dot: var(--pink); /* color of do not disturb dot. */
	--idle-dot: var(--yellow); /* color of idle dot. */
	--streaming-dot: var(--purple); /* color of streaming dot. */

	/* mention/ping and message colors */
	--mention-txt: var(--acc-0); /* color of mention text. */
	--mention-bg: color-mix(in oklch, var(--acc-0), transparent 90%); /* background highlight of mention text. */
	--mention-overlay: color-mix(in oklch, var(--acc-0), transparent 90%); /* overlay color of messages that mention you. */
	--mention-hover-overlay: color-mix(in oklch, var(--acc-0), transparent 95%); /* overlay color of messages that mention you when hovered. */
	--reply-overlay: var(--active); /* overlay color of message you are replying to. */
	--reply-hover-overlay: var(--hover); /* overlay color of message you are replying to when hovered. */

	/* color shades */
	--pink: oklch(73.7% 0.125 11.19);
	--pink-1: oklch(63.7% 0.125 11.19);
	--pink-2: oklch(53.7% 0.125 11.19);
	--purple: oklch(77.15% 0.126 303.9);
	--purple-1: oklch(67.15% 0.126 303.9);
	--purple-2: oklch(57.15% 0.126 303.9);
	--cyan: oklch(78.51% 0.085 228.38);
	--yellow: oklch(87.9% 0.074 84.75);
	--green: oklch(83.5% 0.108 138.15);
	--green-1: oklch(73.5% 0.108 138.15);
	--green-2: oklch(63.5% 0.108 138.15);
	--lavender: oklch(81.66% 0.091 277.31);
	--lavender-1: oklch(71.66% 0.091 277.31);
	--lavender-2: oklch(61.66% 0.091 277.31);
}

