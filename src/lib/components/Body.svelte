<script lang="ts">
    import jumbotron from "../media/abletonJumbo.png";
    import sample1 from "../media/sample1.png";
    import sample2 from "../media/sample2.png";
    import sample3 from "../media/sample3.png";
    import sample4 from "../media/sample4.png";
    import sample5 from "../media/sample5.png";
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
</div>
