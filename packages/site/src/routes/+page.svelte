<script>
  // No script logic needed for static content
</script>

<div class="min-h-screen bg-gray-50 p-6 font-sans text-gray-800 md:p-12">
  <div class="mx-auto max-w-6xl overflow-hidden rounded-xl bg-white shadow-md">
    <!-- Header -->
    <div class="border-b bg-gray-100 px-8 py-6">
      <h1 class="text-4xl font-bold text-gray-900">Lauri Koivisto</h1>
      <p class="mt-1 text-lg text-gray-700">
        Data & AI Engineer | Python • LLMs • Full-Stack Development
      </p>
    </div>

    <!-- Body -->
    <div class="grid grid-cols-1 md:grid-cols-3">
      <!-- Left column -->
      <aside class="space-y-8 border-r bg-gray-50 p-8 md:col-span-1">
        <!-- Contact -->
        <section>
          <h2 class="mb-3 border-b pb-1 text-xl font-semibold text-gray-900">Contact</h2>
          <ul class="space-y-2 text-gray-700">
            <li>📞 +358 XXX</li>
            <li>📧 XXX@gmail.com</li>
            <li>📍 Helsinki, Finland</li>
          </ul>
        </section>

        <!-- Education -->
        <section>
          <h2 class="mb-3 border-b pb-1 text-xl font-semibold text-gray-900">Education</h2>
          <div class="space-y-3">
            <div>
              <h3 class="font-semibold">M.Sc. (Technology)</h3>
              <p class="text-sm text-gray-600">Aalto University, 2017 – 2025</p>
            </div>
            <div>
              <h3 class="font-semibold">B.Sc. (Technology)</h3>
              <p class="text-sm text-gray-600">Aalto University, 2014 – 2017</p>
            </div>
          </div>
        </section>

        <!-- Skills -->
        <section>
          <h2 class="mb-3 border-b pb-1 text-xl font-semibold text-gray-900">Skills</h2>
          <ul class="space-y-2 text-sm">
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

      <!-- Right column -->
      <main class="space-y-10 p-8 md:col-span-2">
        <!-- Profile -->
        <section>
          <h2 class="mb-3 border-b pb-1 text-2xl font-semibold text-gray-900">Profile</h2>
          <p class="leading-relaxed text-gray-700">
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
          <h2 class="mb-3 border-b pb-1 text-2xl font-semibold text-gray-900">
            Selected Work Experience
          </h2>

          <div class="space-y-6">
            <!-- AI Test Engineer -->
            <div>
              <h3 class="text-lg font-semibold">AI Test Engineer — IBM Finland</h3>
              <p class="text-sm text-gray-600">Nov 2024 – Dec 2024 | Helsinki, Finland</p>
              <ul class="mt-2 list-inside list-disc space-y-1 text-gray-700">
                <li>
                  Designed and implemented a training dataset to evaluate translation accuracy
                  across multiple LLM candidates.
                </li>
                <li>
                  Created custom prompt templates and glossaries for linguistic consistency and
                  domain relevance.
                </li>
                <li>Achieved 11% accuracy improvement over non-LLM baseline.</li>
                <li>
                  Evaluated model outputs using automated scoring and manual linguistic review.
                </li>
              </ul>
            </div>

            <!-- Developer – AI Translator UI -->
            <div>
              <h3 class="text-lg font-semibold">Developer – AI Translator UI — IBM Finland</h3>
              <p class="text-sm text-gray-600">Jan 2025 – Feb 2025 | Helsinki, Finland</p>
              <ul class="mt-2 list-inside list-disc space-y-1 text-gray-700">
                <li>
                  Built a full-stack application integrating a translation LLM with a React
                  front-end and Node.js back-end.
                </li>
                <li>
                  Deployed the solution with Docker containers and integrated dynamic translation
                  APIs.
                </li>
                <li>
                  Collaborated with AI engineers to streamline user interaction with the translation
                  pipeline.
                </li>
              </ul>
            </div>

            <!-- Data Scientist -->
            <div>
              <h3 class="text-lg font-semibold">
                Data Scientist — Image Classification Research, IBM Finland
              </h3>
              <p class="text-sm text-gray-600">May 2023 – Aug 2023 | Helsinki, Finland</p>
              <ul class="mt-2 list-inside list-disc space-y-1 text-gray-700">
                <li>
                  Conducted analytics for image classification using Python, TensorFlow, and Keras.
                </li>
                <li>Designed local training and benchmarking pipelines for CNN architectures.</li>
                <li>
                  Improved accuracy and inference time through iterative optimization and
                  preprocessing.
                </li>
              </ul>
            </div>
          </div>
        </section>

        <!-- Projects -->
        <section>
          <h2 class="mb-3 border-b pb-1 text-2xl font-semibold text-gray-900">Projects</h2>

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
      </main>
    </div>
  </div>
</div>
