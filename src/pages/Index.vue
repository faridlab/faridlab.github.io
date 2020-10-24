<template>
  <q-page class="q-pa-md">
    <div class="q-gutter-md row q-my-sm">
      <div class="col"><strong class="text-h5">Personal Detail:</strong></div>
    </div>
    <div class="q-gutter-md row q-my-sm">
      <div class="col">
        <q-input
          label="Name"
          value="Farid Hidayat"
          stack-label
          filled
        />
      </div>
      <div class="col">
        <q-input
          label="Position"
          value="Senior Fullstack Developer"
          stack-label
          filled
        />
      </div>
    </div>

    <div class="q-gutter-md q-my-sm row">
      <div class="col">
        <q-input
          label="About"
          value="Full Stack Developer, Mobile Developer, Technowizard, TechnoArt, Visionary Entrepreneur and Technology lover."
          autogrow
          stack-label
          filled
        />
      </div>
    </div>

    <div class="q-gutter-md row q-my-sm">
      <div class="col">
        <q-input
          label="Email"
          type="email"
          value="e.faridhidayat@gmail.com"
          stack-label
          filled
        />
      </div>
      <div class="col">
        <q-input
          label="Phone"
          type="phone"
          value="+625770900025"
          stack-label
          filled
        />
      </div>
    </div>

    <div class="q-gutter-md row q-my-sm">
      <div class="col">
        <q-input
          label="Country"
          value="Indonesia"
          stack-label
          filled
        />
      </div>
      <div class="col">
        <q-input
          label="City"
          value="South Jakarta"
          stack-label
          filled
        />
      </div>
    </div>

    <div class="q-gutter-md row q-my-sm">
      <div class="col">
        <q-input
          label="Address"
          value="Jl. Pembangunan Bawah RT.006/012 no.24"
          stack-label
          filled
        />
      </div>
      <div class="col-2">
        <q-input
          label="Postal Code"
          value="12330"
          stack-label
          filled
        />
      </div>
    </div>
    <div class="q-gutter-md row q-my-sm">
      <div class="col"><strong class="text-h5">Professional Summary:</strong></div>
    </div>

    <div class="q-gutter-md q-my-sm row">
      <div class="col">
        <q-input
          label="Summary"
          value="Farid Hidayat has 9 years of experience as an Information Technology professional especially in software development field. Currently Farid is a Product Specialist of PT. Sagara Xinix Solusitama (Sagara). Farid is highly motivated and young visionary to technology enhancement for business and economics. As business technologist, Farid has helped many institutions from government and private sector in Indonesia from initial prototype all the way to production release."
          autogrow
          stack-label
          filled
        />
      </div>
    </div>

    <div class="q-gutter-md row q-my-sm">
      <div class="col"><strong class="text-h5">Employment History:</strong></div>
    </div>

    <q-timeline color="secondary" class="q-mt-lg">
      <!-- <q-timeline-entry heading>
        Employment History
      </q-timeline-entry> -->

      <q-timeline-entry avatar="https://media-exp1.licdn.com/dms/image/C4E0BAQH43Ds6vawmCQ/company-logo_200_200/0?e=2159024400&v=beta&t=34brm2OV-Ekhg3Yewur8hT8zFGDk_nJaRWjJKhEPjHs">
        <template v-slot:title>
          Product Development Specialist
        </template>
        <template v-slot:subtitle>
          PT. Sagara Xinix Solusitama &bull; Jul 2019 – Present
        </template>

        <div>
          <ul>
            <li>Coordinate with global teams and assist in development of new products.</li>
            <li>Administer efficient working of cross functional team and maintain interpersonal relations.</li>
            <li>Manage customer services and maintain effective professional relationships with vendors and agents.</li>
            <li>Assist merchandising and sourcing teams for all product development.</li>
            <li>Assist all vendors to select appropriate color and various components.</li>
            <li>Manage all production problems and ensure timely resolution for same.</li>
            <li>Monitor development process and ensure compliance to schedule and timeframe.</li>
            <li>Evaluate all materials for vendors and ensure compliance to standards.</li>
            <li>Coordinate with agents and design new methodologies for product development.</li>
            <li>Provide appropriate reports and assist in technical production to team.</li>
            <li>Motivate and develop direct reports. Provide appropriate guidance and support.</li>
            <li>Analyze current marketing trends and ensure consistency of styling with same.</li>
            <li>Design and maintain master spreadsheet for product development and prepare appropriate reports.</li>
            <li>Review all new orders and ensure accuracy of all quantities.</li>
            <li>Ensure compliance to all instructions from manufacturer.</li>
            <li>Analyze all customer requirements and industry trends and develop new product development programs.</li>
          </ul>
        </div>
      </q-timeline-entry>

      <q-timeline-entry icon="next_week">
        <template v-slot:title>
          Independent Business Owner
        </template>
        <template v-slot:subtitle>
          Utmostphere &bull; Jul 2016 – Present
        </template>

        <div>
          Chief of Everything Officer
        </div>
      </q-timeline-entry>

      <q-timeline-entry avatar="https://lh3.googleusercontent.com/-qkQmt7VqFnw/AAAAAAAAAAI/AAAAAAAAAAA/svK5pmVcCqM/s88-p-k-no-ns-nd/photo.jpg">
        <template v-slot:title>
          Senior Mobile Application Developer
        </template>
        <template v-slot:subtitle>
          PT. Thinksmart Ide Brajendra &bull; Nov 2015 – Jun 2019
        </template>

        <div>
          <ul>
            <li>Establishing a detailed program specification through discussion with clients;</li>
            <li>Clarifying what actions the program is intended to perform;</li>
            <li>Breaking down program specification into its simplest elements and translating this logic into a programming language;</li>
            <li>Devising possible solutions to anticipated problems;</li>
            <li>Working as part of a team, which may be established purely for a particular project to rite a specific section of the program;</li>
            <li>Combining all elements of the program design and testing it;</li>
            <li>Testing sample data-sets to check that output from the program works as intended;</li>
            <li>Conducting testing and installing the program into production;</li>
            <li>Reacting to problems and correcting the program as necessary;</li>
            <li>Evaluating and increasing the program's effectiveness;</li>
            <li>Adapting the program to new requirements, as necessary;</li>
            <li>Conducting user-acceptance testing to ensure the program can be used easily, quickly and accurately;</li>
            <li>Writing detailed documentation for the operation of the program by users and computer operators;</li>
            <li>Consulting manuals, periodicals and technical reports to learn new ways to develop programs and maintain existing skills and knowledge;</li>
            <li>Updating, repairing, modifying and developing existing software and generic applications.</li>
          </ul>
        </div>
      </q-timeline-entry>

      <q-timeline-entry avatar="https://media-exp1.licdn.com/dms/image/C4E0BAQH43Ds6vawmCQ/company-logo_200_200/0?e=2159024400&v=beta&t=34brm2OV-Ekhg3Yewur8hT8zFGDk_nJaRWjJKhEPjHs">
        <template v-slot:title>
          Technical Manager
        </template>
        <template v-slot:subtitle>
          PT. Sagara Xinix Solusitama &bull; Jan 2014 – Oct 2015
        </template>

        <div>
          <strong>Technical</strong>
          <ul>
            <li>Must ensure teams follow the correct procedures, policies and documentation requirements across project phases</li>
            <li>Able to guide the team through the development, testing and implementation stages and review the completed work effectively</li>
            <li>Provide direction and technical expertise in design, development and systems integration</li>
            <li>Able to make quick decisions and solve technical problems to provide an efficient environment for project implementation</li>
            <li>Identify resource and equipment requirements, efficient capacity planning and manage software and hardware availability</li>
            <li>Must provide technical training to teams when required and serve as a technical mentor to team members</li>
          </ul>

          <strong>Management</strong>
          <ul>
            <li>Ensure standard operating procedures and project guidelines are in place</li>
            <li>Task allocation and performance evaluation of team members</li>
            <li>Project scheduling and resource management</li>
            <li>Planning, budgeting and reporting on projects</li>
            <li>Make presentations on project status, present monthly and annual reports to senior management</li>
            <li>Meet with client teams and gather requirements, conduct regular team meetings and track project progress</li>
            <li>Interview candidates and hire resources</li>
            <li>Conduct performance reviews of team members and identify areas of improvement, give feedback and recommend for promotions or salary increments</li>
            <li>Estimate project budgets, coordinate with finance department for funds and plan for purchasing of equipment and hardware in a cost-effective way</li>
            <li>Provide an efficient working atmosphere to project teams and ensure objectives are met within stipulated time</li>
          </ul>
        </div>
      </q-timeline-entry>

      <q-timeline-entry avatar="https://media-exp1.licdn.com/dms/image/C4E0BAQH43Ds6vawmCQ/company-logo_200_200/0?e=2159024400&v=beta&t=34brm2OV-Ekhg3Yewur8hT8zFGDk_nJaRWjJKhEPjHs">
        <template v-slot:title>
          Team Lead
        </template>
        <template v-slot:subtitle>
          PT. Sagara Xinix Solusitama &bull; Jan 2013 – Dec 2013
        </template>

        <div>
          <ul>
            <li>Delegate duties and tasks within the IT department.</li>
            <li>Review completed tasks to ascertain compliance with standards.</li>
            <li>Monitor all team members and provide necessary advice and guidance.</li>
            <li>Perform periodic risk assessments and initiate risk control strategies.</li>
            <li>Coach all team members and motivate them to produce desired results.</li>
            <li>Organize regular seminars and trainings to teach team members new techniques and methods.</li>
            <li>Keep up with trends in the constantly evolving information technology industry.</li>
            <li>Perform regular IT audit to discover areas of weaknesses and fortify them.</li>
            <li>Work alongside other departments to achieve company goals and visions.</li>
            <li>Write and forward regular reports to the management.</li>
            <li>Provide solution to any complex IT related challenges in the organization.</li>
            <li>Perform regular appraisal of team member’s performance and devise strategies to help with improvement.</li>
            <li>Carry out in-depth research to reveal new and better methods of handling functions within the department.</li>
            <li>Ensure that the company’s data and information are protected from unauthorized access.</li>
            <li>Supervise repair and maintenance of all IT gadgets.</li>
          </ul>
        </div>
      </q-timeline-entry>

      <q-timeline-entry avatar="https://media-exp1.licdn.com/dms/image/C4E0BAQH43Ds6vawmCQ/company-logo_200_200/0?e=2159024400&v=beta&t=34brm2OV-Ekhg3Yewur8hT8zFGDk_nJaRWjJKhEPjHs">
        <template v-slot:title>
          Junior Programmer
        </template>
        <template v-slot:subtitle>
          PT. Sagara Xinix Solusitama &bull; Mar 2012 – Dec 2012
        </template>

        <div>
          <ul>
            <li>Strong knowledge of PHP web frameworks Codeigniter and Laravel</li>
            <li>Understanding the fully synchronous behavior of PHP</li>
            <li>Understanding of MVC design patterns</li>
            <li>Basic understanding of front-end technologies, such as JavaScript, HTML5, and CSS3</li>
            <li>Knowledge of object oriented PHP programming</li>
            <li>Understanding accessibility and security compliance</li>
            <li>Strong knowledge of the common PHP or web server exploits and their solutions</li>
            <li>Understanding fundamental design principles behind a scalable application</li>
            <li>User authentication and authorization between multiple systems, servers, and environments</li>
            <li>Integration of multiple data sources and databases into one system</li>
            <li>Familiarity with limitations of PHP as a platform and its workarounds</li>
            <li>Creating database schemas that represent and support business processes</li>
            <li>Familiarity with SQL/NoSQL databases and their declarative query languages</li>
            <li>Proficient understanding of code versioning tools, such as Git</li>
          </ul>
        </div>
      </q-timeline-entry>

      <q-timeline-entry icon="work">
        <template v-slot:title>
          Junior Programmer
        </template>
        <template v-slot:subtitle>
          Kementerian Pendidikan Nasional &bull; Mar 2011 – Feb 2012
        </template>
      </q-timeline-entry>
    </q-timeline>

  </q-page>
</template>

<script>
export default {
  name: 'Profile',
  data () {
    return {
      about: 'Farid Hidayat has 9 years of experience as an Information Technology professional especially in software development field. Currently Farid is a Product Specialist of PT. Sagara Xinix Solusitama (Sagara). Farid is highly motivated and young visionary to technology enhancement for business and economics. As business technologist, Farid has helped many institutions from government and private sector in Indonesia from initial prototype all the way to production release.'
    }
  }
}

</script>
