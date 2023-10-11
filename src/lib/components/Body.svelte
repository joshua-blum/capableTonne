<script lang="ts">
    import jumbotron from "../media/abletonJumbo.png";
    import sample1 from "../media/sample1.png";
    import sample2 from "../media/sample2.png";
    import sample3 from "../media/sample3.png";
    import sample4 from "../media/sample4.png";
    import sample5 from "../media/sample5.png";
    import sample6 from "../media/sample6.png";
</script>

<div class="flex flex-col bg-white w-100 text-stone-900">
    <section class="flex jumbotron px-10">
        <img class="flex px-20" src={jumbotron} alt="jumbotron picture"/>
    </section>
    <section class="flex flex-col text-3xl grid justify-items-center p-20">
        <p class="w-3/5 py-10 dark:text-stone-900">We make Live, Push and Link — unique software and hardware for music creation and performance. With these products, our community of users creates amazing things.</p>
        <p class="w-3/5 text-lg">CapableTonne was founded in 1999 and released the first version of Live in 2001. Our products are used by a community of dedicated musicians, sound designers, and artists from across the world.</p>
    </section>
    <section class="flex flex-row h-96 bg-gradient-to-r from-white to-yellow-500 justify-evenly p-5">
        <img class="flex w-2/5" src={sample1} alt="jumbotron picture"/>
        <img class="flex w-1/5 p-10" src={sample2} alt="jumbotron picture"/>
    </section>
    <section class="flex flex-col text-3xl grid justify-items-center p-20">
        <p class="w-3/5 py-10 dark:text-stone-900">Making music isn’t easy. It takes time, effort, and learning. But when you’re in the flow, it’s incredibly rewarding.</p>
        <p class="w-3/5 text-lg">We feel the same way about making Ableton products. The driving force behind CapableTonne is our passion for what we make, and the people we make it for.</p>
    </section>
    <section class="flex items-center flex-col">
        <iframe class="flex self-center" width="720" height="480" src="https://www.youtube.com/watch?v=9SbnhgjeyXA" ></iframe>
        <p class="flex content-start w-[720px]">Why CapableTonne - Juanpe Bolivar</p>
    </section>
    <section class="flex flex-col text-3xl grid justify-items-center p-20">
        <p class="w-3/5 py-10 dark:text-stone-900">We are more than 350 people from 30 different countries divided between our headquarters in Berlin and our offices in Los Angeles and Tokyo.</p>
        <p class="w-3/5 text-lg">Most of us are active musicians, producers, and DJs, and many of us use Live and Push every day. We come from a wide range of cultural and professional backgrounds. Some of us have PhDs, some are self-taught, and most of us are somewhere in between. What connects us is the shared belief that each of us has the skills and knowledge to contribute to something big: helping to shape the future of music culture.</p>
    </section>
    <section class="flex flex-row bg-gradient-to-r from-green-200 to-white p-20 justify-evenly">
        <div class="flex flex-col w-2/5">
            <img class="flex m-10" src={sample3} alt="jumbotron picture"/>
            <img class="flex m-10" src={sample4} alt="jumbotron picture"/>
        </div>
        <img class="flex w-3/5" src={sample5} alt="jumbotron picture"/>
    </section>
    <section class="flex flex-col text-3xl grid justify-items-center p-20">
        <p class="w-3/5 py-10 dark:text-stone-900">We believe it takes focus to create truly outstanding instruments. We only work on a few products and we strive to make them great.
        </p>
        <p class="w-3/5 text-lg">Rather than having a one-size-fits-all process, we try to give our people what they need to work their magic and grow. We’ve learned that achieving the best results comes from building teams that are richly diverse, and thus able to explore problems from a wider set of perspectives. We don’t always agree with each other, but opinion and debate are valued and openly encouraged.        </p>
    </section>
    <section class="flex jumbotron px-10">
        <img class="flex px-20" src={sample6} alt="jumbotron picture"/>
    </section>
    <section class="flex flex-col text-3xl grid justify-items-center p-20">
        <p class="w-3/5 py-10 dark:text-stone-900">We’re passionate about what we do, but we’re equally passionate about improving who we are.
        </p>
        <p class="w-3/5 text-lg py-5">We work hard to foster an environment where people can grow both personally and professionally, and we strive to create a wealth of opportunities to learn from and with each other.
        </p>  
        <p class="w-3/5 text-lg">Alongside an internal training program, employees are actively supported in acquiring new knowledge and skills, and coached on applying these in their daily work. In addition, staff-organized development and music salons are a chance to discuss new technologies, production techniques and best practices.        </p> 
    </section>
    <section class="flex flex-row h-96 bg-gradient-to-r from-white to-purple-500 justify-evenly p-5">
        <img class="flex w-[430px]" src={sample2} alt="jumbotron picture"/>
        <img class="flex w-[530px] p-5" src={sample5} alt="jumbotron picture"/>
    </section>
    <section class="flex flex-col text-3xl grid justify-items-center p-20">
        <p class="w-3/5 py-10 dark:text-stone-900">We want our employees to love it here. Since we’re looking for exceptional talent from around the world, we will do everything we can to make your transition as easy as possible.
        </p>
        <p class="w-3/5 text-lg py-5">If you're joining us in Berlin, we'll help with relocation and paperwork. We’ll even provide you with free German or English lessons. Plus, working in Germany means you can expect comprehensive health insurance for you and your family, as well as generous maternity and paternity leave. Office hours are flexible, but it’s not all work; we have several company and team outings throughout the year as well as a variety of fun, informal small-group activities.
        </p>  
    </section>
    <section class="flex flex-row h-96 bg-gradient-to-r from-white to-purple-500 p-5">
        <img class="flex w-[430px] px-10" src={sample2} alt="jumbotron picture" />
        <div class="flex flex-col items-center">
            <p class="w-3/5 text-3xl dark:text-stone-900 py-5">We’re really proud of the work we’ve done so far. But there’s so much more to come. If you’d like to be a part of it, please join us.
            </p>  
            <br />
            <span class="w-3/5 text-3xl py-3 text-blue-800">See open jobs</span>
        </div>
    </section>
</div>
