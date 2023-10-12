<script lang="ts">
    import logo from "../media/ableton-hallmark.ef5355379032.svg";
    let emailAddress: String;
    function subscribeToNewsletter(email: String){
        console.log('we would be making an api request with the following email address: ', email);
        emailAddress = '';
    }
</script>

<footer class="flex bg-white flex-col p-20 text-stone-900">
    <h2 class="flex m-10 text-5xl">CapableTonne</h2>
    <section class="flex flex-row p-10 justify-start">
        <div class="mainLinks flex flex-col w-1/5">
            <ul>
                <li>Register Live or Push</li>
                <li>About CapableTonne</li>
                <li>Jobs</li>
                <div class="socials flex flex-row">
                    insert social images here
                </div>
            </ul>
        </div>
        <div class="educationLinks flex flex-col w-1/5">
            <h4>Education</h4>
            <ul>
                <li>Offers for students and teachers</li>
                <li>CapableTonne for the classroom</li>
                <li>CapableTonne for colleges and universities</li>
            </ul>
        </div>
        <div class="newsletter flex flex-col pl-[55px] w-2/5">
            <h4>Sign up for our newsletter</h4>
            <p>Enter your email address to stay up to date with the latest offers, tutorials, downloads, surveys and more.
            </p>
            <div class="newsletterField py-3">
                <input type="text" placeholder="Email address..." bind:value={emailAddress}/>
                <button 
                    class="bg-orange-800 text-white p-2 m-0 buttonCustom"
                    type="button" 
                    on:click={() => {subscribeToNewsletter(emailAddress)}}>Subscribe</button>
            </div>
        </div>
    </section>
    <section class="flex flex-row p-10">
        <div class="communityLinks flex flex-col w-1/5">
            <h4>Community</h4>
            <ul>
                <li>Find CapableTonne User Groups</li>
                <li>Find certified training</li>
                <li>Become a certified trainer</li>
            </ul>
        </div>
        <div class="langAndLoc flex flex-col px-10 w-2/5">
            <h4>Language and Location</h4>
            <div class="dropdown">
                <button>Language</button>
                <div class="dropdownMenu">
                    Dropdown content
                </div>
            </div>

        </div>
    </section>
    <section class="flex flex-row justify-between px-6 py-3">
        <ul class="flex flex-row items-center">
            <li class="px-3">Contact Us</li>
            <li class="px-3">Press Resources</li>
            <li class="px-3">Legal Info</li>
            <li class="px-3">Privacy Policy</li>
            <li class="px-3">Cookie Settings</li>
            <li class="px-3">Imprint</li>
        </ul>
        <div class="finalStuff flex flex-row">
            <p class="px-3">Made in Berlin</p>
            <img src={logo} alt="logo" />
        </div>
    </section>
</footer>

<style>
    .buttonCustom {
        transition: background-color 50ms ease-in-out, padding 50ms ease-in-out;
        border-radius: 25px;
    }
    .buttonCustom:hover {
        background-color: orange;
        padding: 9px;
        transition: background-color 50ms ease-in-out, padding 50ms ease-in-out
    }
    .buttonCustom:active {
        background-color: yellow;
        transition: background-color 50ms ease-in, padding 50ms ease-in-out
    }

    /* .dropdown {
        position:relative;
    }

    .dropdownMenu {
        position:absolute;
        left: 0;
        top: calc(100% + 0.5rem);
        padding: 0.75rem;
        border-radius: 0.25rem;
        box-shadow: 0 2px 5px 0 rgba(0,0,0,.5);
        transform: translateY(-10px);
        opacity: 0;
        pointer-events: none;
        transition: opacity 150ms ease-in-out, transform 150ms ease-in-out;
    }

    .dropdownContent {

    } */
</style>