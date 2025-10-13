<script>
  // No script logic needed for static content
</script>

<div class="min-h-screen text-gray-800">
  <div class="page">
    <!-- Body -->
    <div class="grid grid-cols-[var(--left-side-width)_auto_1fr]">
      <!-- Left column -->

      <aside class="space-y-8 p-8">
        <figure class="flex items-center justify-center pt-6">
          <img
            src="./portrait1.jpg"
            alt="my face"
            class=" h-[192px] w-[192px] rounded-full object-cover [object-position:40%_15%]"
          />
        </figure>
        <!-- Contact -->
        <section>
          <h2 class="mb-3 pb-1 text-xl font-extrabold uppercase text-gray-900">Contact</h2>
          <ul class="space-y-2 text-gray-700">
            <li>📞 +358 XXX</li>
            <li>📧 XXX@gmail.com</li>
            <li>📍 Helsinki, Finland</li>
          </ul>
        </section>

        <!-- Education -->
        <section>
          <h2 class="mb-3 pb-1 text-xl font-extrabold uppercase text-gray-900">Education</h2>
          <div class="space-y-3">
            <div>
              <h3 class="font-semibold">M.Sc. (Technology), Speech and Signal Processing</h3>
              <p class="text-sm text-gray-600">Aalto University, 2017 – 2025</p>
              <p class="mt-1 text-gray-700">
                Studied speech recognition, natural language processing, and machine learning
                methods for audio and linguistic data.
              </p>
            </div>
            <div>
              <h3 class="font-semibold">B.Sc. (Technology), Automation and Systems Technology</h3>
              <p class="text-sm text-gray-600">Aalto University, 2014 – 2017</p>
              <p class="mt-1 text-gray-700">
                Studied control systems, robotics, and embedded automation.
              </p>
            </div>
          </div>
        </section>

        <!-- Skills -->
        <section>
          <h2 class="mb-3 pb-1 text-xl font-extrabold uppercase text-gray-900">Skills</h2>
          <ul class="space-y-2 text-sm">
            <li>
              <strong>Finnish:</strong> Native <br /> <strong>English:</strong> Fluent
            </li>
            <li>
              <strong>Languages & Frameworks:</strong> Python, JavaScript, TypeScript, SQL, Node.js,
              React
            </li>
            <li>
              <strong>AI / ML Tools:</strong> TensorFlow, Keras, scikit-learn, LangChain
            </li>
            <li>
              <strong>Cloud & DevOps:</strong> Docker, AWS, Azure, IBM Cloud
            </li>
            <li>
              <strong>Data & Databases:</strong> Pandas, PostgreSQL
            </li>
            <li>
              <strong>LLM / NLP:</strong> Prompt design, evaluation pipelines, conversational AI
            </li>
            <li>
              <strong>Other:</strong> Agile, Git, REST APIs
            </li>
          </ul>
        </section>
      </aside>

      <!-- Divider -->
      <div
        aria-hidden="true"
        class="h-[90%] w-[3px] self-center justify-self-center rounded-full bg-gray-400/70"
      ></div>

      <!-- Right column -->
      <main class="space-y-10 p-8">
        <!-- Profile -->
        <section>
          <!-- Header -->
          <div class=" py-6">
            <h1 class="ml-[-2px] text-5xl font-bold text-gray-900">Lauri Koivisto</h1>
            <p class="mt-1 pl-[1px] text-lg text-gray-700">Data & AI Engineer</p>
            <p class="mt-1 pl-[1px] text-sm text-gray-700">
              Python • LLMs • Full-Stack Development
            </p>
          </div>
          <p class=" pl-[1.5px] leading-relaxed text-gray-700">
            Data & AI Engineer with experience designing and implementing AI-powered solutions
            utilizing natural language and translation. Strong foundation in Python, data
            engineering, and full-stack development using modern frameworks. Skilled at applying
            machine learning and LLM technologies to build practical, scalable systems that deliver
            measurable value. Experienced in cross-functional collaboration and iterative
            development in agile environments.
          </p>
        </section>
        <!-- Work Experience -->
        <section>
          <h2 class="mb-3 pb-1 text-[22px] font-extrabold uppercase text-gray-900">
            Selected Work Experience
          </h2>

          <!-- IBM Finland -->
          <div class="pl-[1px]">
            <h3 class="text-lg font-semibold">AI and Data Engineer, IBM Finland</h3>
            <p class="text-sm text-gray-600">May 2022 – July 2025 | Helsinki, Finland</p>
            <div class="mt-2 space-y-2 pl-[1.5px] text-gray-700">
              <p class="leading-relaxed text-gray-700">
                Worked on several AI-focused projects including translation evaluation, chatbot
                development, and image classification research. Designed and implemented datasets
                and prompt templates to assess multilingual LLM translation accuracy, leading to an
                11% improvement over baseline models.
              </p>
              <p class="leading-relaxed text-gray-700">
                Built and deployed a full-stack translation interface integrating React, Node.js,
                and Docker for real-time translation workflows.
              </p>
              <p class="leading-relaxed text-gray-700">
                Conducted CNN-based image classification research with TensorFlow and Keras,
                optimizing model performance. Additionally, built public-sector chatbots using
                Watson Assistant and Discovery, and provided training for chatbot maintainers.
              </p>
            </div>
          </div>
        </section>
      </main>
    </div>
  </div>
  <div class="page">
    <!-- Body -->
    <div class="grid grid-cols-[var(--left-side-width)_auto_1fr]">
      <!-- Left column -->

      <aside class="space-y-8 p-8">
        <!-- Projects -->
        <section>
          <h2 class="mb-3 pb-1 text-2xl font-semibold text-gray-900">Projects</h2>

          <div class="space-y-4">
            <div>
              <a
                href="https://koodilauri.github.io/"
                class="font-medium text-blue-600 hover:underline">Personal Portfolio</a
              >
              — Developed a Next.js + Tailwind CSS portfolio site to present projects and experience
              in a visually appealing format.
            </div>
            <div>
              <a
                href="https://github.com/koodilauri/speaker-verification"
                class="font-medium text-blue-600 hover:underline">Speaker Verification (Thesis)</a
              >
              — Trained a CNN model for speaker recognition with voice features like jitter & shimmer.
            </div>
            <div>
              <a
                href="http://go.vaisala.com/keravaradar/"
                class="font-medium text-blue-600 hover:underline">Vaisala Radar Web App</a
              >
              — Developed backend and frontend with TypeScript, React, and Node.js.
            </div>
            <div>
              <a
                href="https://d386g19k2b21z4.cloudfront.net/"
                class="font-medium text-blue-600 hover:underline">Speedrun Fansite</a
              >
              — Created a React/Node project for submitting and managing video game speedruns.
            </div>
          </div>
        </section>
      </aside>

      <!-- Divider -->
      <div
        aria-hidden="true"
        class="h-[90%] w-[3px] self-center justify-self-center rounded-full bg-gray-400/70"
      ></div>

      <!-- Right column -->
      <main class="space-y-10 p-8">
        <!-- Work Experience -->
        <section>
          <div class="space-y-6 pl-[1px]">
            <!-- Thesis Worker -->
            <div>
              <h3 class="text-lg font-semibold">Thesis Worker, Aalto University</h3>
              <p class="text-sm text-gray-600">April 2020 – Sep 2020 | Helsinki, Finland</p>
              <p class="mt-2 pl-[1.5px] leading-relaxed text-gray-700">
                For my thesis project I researched if adding new features to a Convolutional Neural
                Network (CNN) model would improve its accuracy in speaker recognition. I compared
                the model to a baseline and after evaluating the error rates my research found that
                features such as jitter and shimmer can improve speaker recognition.
              </p>
            </div>

            <!-- Web Developer -->
            <div>
              <h3 class="text-lg font-semibold">Web Developer, Vaisala</h3>
              <p class="text-sm text-gray-600">June 2018 – Sep 2018 | Helsinki, Finland</p>
              <p class="mt-2 pl-[1.5px] leading-relaxed text-gray-700">
                I worked as a developer in the Weather Radar team, with the goal to use the image
                export functionality of IRIS Focus to display images at go.vaisala.com/keravaradar.
                I developed most of the backend and frontend with Typescript, React and Node.js.
                Another project I worked o
              </p>
            </div>
          </div>
        </section>
      </main>
    </div>
  </div>
</div>

<style lang="postcss">
  @reference "#app.css";
  :root {
    --left-side-width: 256px;
  }
  .page {
    @apply mx-[auto] flex min-h-[29.7cm] max-w-[800px] flex-col items-center px-4 text-sm md:px-16;
  }
</style>
