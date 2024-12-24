<svelte:head>
    <title>@loopsvariables</title>
    <meta name="description" content="In 2003 I figured out I could get paid to build stuff on the www. Thanks Tim!" />
    <meta name="robots" content="index, follow" />
    <link rel="canonical" href="https://loopsandvariables.com" />
    
    <!-- Mobile App Meta Tags -->
    <meta name="mobile-web-app-capable" content="yes" />
    <meta name="apple-mobile-web-app-capable" content="yes" />
    <meta name="apple-mobile-web-app-title" content="@loopsvariables" />
    <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent" />
    <meta name="theme-color" content="#000000" />

    <!-- Open Graph / Facebook -->
    <meta property="og:type" content="website" />
    <meta property="og:url" content="https://loopsandvariables.com" />
    <meta property="og:title" content="@loopsvariables" />
    <meta property="og:description" content="In 2003 I figured out I could get paid to build stuff on the www. Thanks Tim!" />
    <meta property="og:image" content="https://raw.githubusercontent.com/loopsandvariables/x-themed-profile/refs/heads/main/static/images/desktop-mobile-mockup.png" />

    <!-- Twitter -->
    <meta name="twitter:card" content="summary_large_image" />
    <meta name="twitter:url" content="https://loopsandvariables.com" />
    <meta name="twitter:title" content="@loopsvariables" />
    <meta name="twitter:description" content="In 2003 I figured out I could get paid to build stuff on the www. Thanks Tim!" />
    <meta name="twitter:image" content="https://raw.githubusercontent.com/loopsandvariables/x-themed-profile/refs/heads/main/static/images/desktop-mobile-mockup.png" />
    <meta name="twitter:creator" content="loopsvariables" />
</svelte:head>

<div class="w-full m-auto max-w-[1400px]">
    <div class="grid grid-cols-12 mx-auto lg:gap-16 xl:gap-20 2xl:gap-24">
        <!-- Left Column -->
        <div class="top-0 flex flex-col col-span-12 gap-6 p-6 overflow-y-auto lg:h-screen lg:sticky lg:col-span-6 xl:col-span-5 md:gap-8 lg:gap-10 xl:gap-12 2xl:gap-14 md:p-12 lg:p-16 xl:p-20 2xl:p-24 lg:pr-0 xl:pr-0 2xl:pr-0">
            <div class="flex flex-col items-center md:flex-row">
                <a class="flex flex-col items-center justify-center gap-3 pt-5 text-center md:pt-0 md:justify-start md:text-left md:flex-row md:gap-5 lg:gap-4 xl:gap-6" href="https://x.com/intent/follow?screen_name=loopsvariables" target="_blank">
                    <img src="/images/profile.jpg" alt="Henry" class="w-20 h-20 rounded-full md:w-16 md:h-16" />
                    <div class="flex flex-col items-center justify-center text-xl md:items-start md:justify-start md:text-xl xl:text-xl">
                        <span class="flex items-center gap-[0.3em] font-extrabold">
                            Henry 
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" width="24" height="24" fill="currentColor" aria-label="BadgeCheck Icon" class="text-[#4a99e9] w-[1em] h-[1em]"><path d="M256 0c36.8 0 68.8 20.7 84.9 51.1C373.8 41 411 49 437 75s34 63.3 23.9 96.1C491.3 187.2 512 219.2 512 256s-20.7 68.8-51.1 84.9C471 373.8 463 411 437 437s-63.3 34-96.1 23.9C324.8 491.3 292.8 512 256 512s-68.8-20.7-84.9-51.1C138.2 471 101 463 75 437s-34-63.3-23.9-96.1C20.7 324.8 0 292.8 0 256s20.7-68.8 51.1-84.9C41 138.2 49 101 75 75s63.3-34 96.1-23.9C187.2 20.7 219.2 0 256 0zM369 209c9.4-9.4 9.4-24.6 0-33.9s-24.6-9.4-33.9 0l-111 111-47-47c-9.4-9.4-24.6-9.4-33.9 0s-9.4 24.6 0 33.9l64 64c9.4 9.4 24.6 9.4 33.9 0L369 209z"/></svg>
                        </span>
                        <span class="font-medium opacity-60">@loopsvariables</span>
                    </div>
                </a>
                <div class="flex items-center gap-5 mt-6 md:mt-0 xl:gap-6 md:ml-auto">
                    <a class="text-lg xl:text-xl font-bold rounded-full bg-dark dark:bg-light hover:opacity-80 px-[1em] py-[0.5em] text-light dark:text-dark" href="https://x.com/intent/follow?screen_name=okbudda" target="_blank">Follow</a>
                </div>
            </div>

            <!-- Bio Text -->
            <div class="px-5 text-xl text-center md:text-left md:text-2xl lg:text-2xl xl:text-2xl md:px-0">
                <p>I created this template for my personal page. It's simple, responsive, and kinda looks like X? Get it from <a href="https://github.com/loopsandvariables/x-themed-profile" class="underline" target="_blank">GitHub</a>. My
                    <a href="https://loopsandvariables.com" class="underline" target="_blank">original page</a> is here.
                </p>
                <p class="mt-[1em]"><a href="/updates" class="underline">Join my email list</a> for product updates and free stuff I make for other solo builders.</p>
            </div>

            <!-- Social Links -->
            <div class="flex items-center justify-center gap-10 py-6 mt-auto lg:py-0 md:justify-start">
                <!-- Social icons (Twitter, Dribbble, GitHub, CodePen) -->
                <a class="p-2 -m-2 opacity-100 hover:opacity-60" 
                   href="https://x.com/intent/follow?screen_name=loopsvariables" 
                   target="_blank"
                   aria-label="Follow on X (formerly Twitter)">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" width="24" height="24" fill="currentColor" aria-label="XTwitter Icon" class="w-8 h-8"><path d="M389.2 48h70.6L305.6 224.2 487 464H345L233.7 318.6 106.5 464H35.8L200.7 275.5 26.8 48H172.4L272.9 180.9 389.2 48zM364.4 421.8h39.1L151.1 88h-42L364.4 421.8z"/></svg>
                </a>
                <!-- Add other social icons here -->
            </div>
        </div>

        <!-- Right Column -->
        <div class="col-span-12 p-6 -mt-6 lg:col-span-6 xl:col-span-7 md:p-12 lg:p-16 xl:p-20 2xl:p-24 lg:pl-0 xl:pl-0 2xl:pl-0 md:-mt-12 lg:mt-0">
            <div class="flex flex-col gap-6 text-base md:text-xl md:gap-6 lg:gap-7 xl:gap-8">
                <!-- Project Cards -->
                <!-- Add your project cards here following the same pattern -->
            </div>
        </div>
    </div>
</div>

<style lang="postcss">
    /* Add any custom styles here if needed */
    :global(html) {
        @apply antialiased;
    }
    
    :global(body) {
        @apply font-sans text-base antialiased bg-light dark:bg-dark text-dark dark:text-light selection:bg-dark selection:text-light dark:selection:bg-light dark:selection:text-dark;
    }
</style>
