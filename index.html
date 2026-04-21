import { useState, useEffect } from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { Input } from "@/components/ui/input";

export default function StudyPlannerApp() {
  const [page, setPage] = useState("home");

  const [tasksByDate, setTasksByDate] = useState({});
  const [selectedDate, setSelectedDate] = useState(
    new Date().toISOString().split("T")[0]
  );
  const [taskInput, setTaskInput] = useState("");

  const [time, setTime] = useState(0);
  const [running, setRunning] = useState(false);

  useEffect(() => {
    const saved = localStorage.getItem("plannerData");
    if (saved) setTasksByDate(JSON.parse(saved));
  }, []);

  useEffect(() => {
    localStorage.setItem("plannerData", JSON.stringify(tasksByDate));
  }, [tasksByDate]);

  useEffect(() => {
    let interval;
    if (running) {
      interval = setInterval(() => setTime((t) => t + 1), 1000);
    }
    return () => clearInterval(interval);
  }, [running]);

  const tasks = tasksByDate[selectedDate] || [];

  const addTask = () => {
    if (!taskInput.trim()) return;
    setTasksByDate({
      ...tasksByDate,
      [selectedDate]: [...tasks, { text: taskInput, done: false }],
    });
    setTaskInput("");
  };

  const toggleTask = (i) => {
    const updated = [...tasks];
    updated[i].done = !updated[i].done;
    setTasksByDate({ ...tasksByDate, [selectedDate]: updated });
  };

  const deleteTask = (i) => {
    const updated = tasks.filter((_, index) => index !== i);
    setTasksByDate({ ...tasksByDate, [selectedDate]: updated });
  };

  const formatTime = (t) => {
    const m = Math.floor(t / 60);
    const s = t % 60;
    return `${m}:${s.toString().padStart(2, "0")}`;
  };

  const Nav = () => (
    <div className="flex justify-between items-center px-8 py-6 border-b bg-white/70 backdrop-blur">
      <h1
        className="text-xl font-bold cursor-pointer"
        onClick={() => setPage("home")}
      >
        STUDYFLOW
      </h1>
      <div className="flex gap-6 text-sm">
        <button onClick={() => setPage("learn")} className="hover:underline">
          Learn
        </button>
        <button onClick={() => setPage("focus")} className="hover:underline">
          Focus
        </button>
        <button
          onClick={() => setPage("planner")}
          className="hover:underline"
        >
          Planner
        </button>
      </div>
    </div>
  );

  return (
    <div className="min-h-screen bg-gradient-to-br from-indigo-100 via-white to-blue-100">
      <Nav />

      {/* HOME */}
      {page === "home" && (
        <div className="px-8 py-16 max-w-6xl mx-auto space-y-10">
          <h2 className="text-5xl font-bold leading-tight">
            Study smarter.
            <br /> Not longer.
          </h2>

          <p className="text-gray-600 max-w-2xl">
            Most students don’t struggle because they’re lazy — they struggle
            because they wait to feel ready.
          </p>

          <Card>
            <CardContent className="p-6 space-y-4">
              <h3 className="text-xl font-bold">📘 What this website is</h3>
              <p>
                STUDYFLOW is a student-focused learning system designed to help you study more effectively using psychology-backed methods.
              </p>
              <p>
                It combines three core tools:
              </p>
              <ul className="space-y-1 text-gray-700">
                <li>🧠 Learn — understand how learning actually works</li>
                <li>⚡ Focus — build deep concentration systems</li>
                <li>🗓 Planner — organize tasks and track daily progress</li>
              </ul>
              <p className="font-semibold">
                The goal is simple: help you study smarter, not longer.
              </p>
            </CardContent>
          </Card>

          <Card>
            <CardContent className="p-6 space-y-2">
              <p>Progress doesn’t start with motivation.</p>
              <p>It starts with action.</p>
              <p className="font-semibold">
                Small steps done consistently beat perfect plans.
              </p>
            </CardContent>
          </Card>

          <img
            src="https://images.unsplash.com/photo-1523240795612-9a054b0db644"
            className="rounded-2xl shadow-lg w-full object-cover max-h-[420px]"
          />

          <Card>
            <CardContent className="p-6 space-y-3">
              <h3 className="text-xl font-bold">What actually matters</h3>
              <ul className="space-y-2 text-gray-700">
                <li>• Focus beats time spent</li>
                <li>• Starting beats planning forever</li>
                <li>• Consistency beats intensity</li>
                <li>• Deep work beats multitasking</li>
              </ul>
            </CardContent>
          </Card>

          <img
            src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f"
            className="rounded-2xl shadow-lg w-full object-cover max-h-[420px]"
          />
        </div>
      )}
{/* LEARN */}
      {page === "learn" && (
<div className="px-8 py-16 max-w-5xl mx-auto space-y-10">
  <div className="grid md:grid-cols-3 gap-4">
    <img src="https://images.unsplash.com/photo-1503676260728-1c00da094a0b" className="rounded-xl shadow" />
    <img src="https://images.unsplash.com/photo-1454165804606-c3d57bc86b40" className="rounded-xl shadow" />
    <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085" className="rounded-xl shadow" />
  </div>

  <Card>
    <CardContent className="p-6 space-y-5">

      <h2 className="text-3xl font-bold">🧠 Cognitive architecture of learning (2025–2026)</h2>

      <p>
        This expanded report incorporates 2025–2026 psychological research to explain how distraction impacts academic performance through working memory, attention, and long-term encoding systems.
      </p>

      <h3 className="text-xl font-semibold">1. 🧠 Cognitive Load & Attention Bottleneck</h3>
      <p>
        Learning is constrained by working memory limits. Recent studies (Mou et al., 2024; Liang & Chen, 2025) show that technology creates extraneous cognitive load.
      </p>
      <p>
        Even a silent phone forces inhibitory control — your brain spends energy resisting it instead of learning.
      </p>
      <p>
        This reduces germane load, which is the mental capacity needed to actually understand and store new knowledge.
      </p>

      <p>
        🧠 Myth: Multitasking improves productivity
      </p>
      <p>
        ❌ Reality: The brain switches tasks rapidly instead of doing them simultaneously, reducing accuracy and comprehension.
      </p>

      <h3 className="text-xl font-semibold">2. ⚡ Attention Residue (Hidden Cost)</h3>
      <p>
        Research shows that after switching tasks, part of your attention remains stuck on the previous task.
      </p>
      <p>
        This “residue” creates mental fog that can last over 20 minutes.
      </p>
      <p>
        Frequent phone checking prevents full cognitive recovery, keeping you in shallow processing mode.
      </p>

      <h3 className="text-xl font-semibold">3. 🔁 Zeigarnik Effect (Open Loops)</h3>
      <p>
        Unfinished tasks or notifications stay active in memory longer than completed ones.
      </p>
      <p>
        These “open loops” create intrusive thoughts that constantly pull attention away from studying.
      </p>
      <p>
        Closing loops requires either completing tasks or removing triggers (like notifications).
      </p>

      <h3 className="text-xl font-semibold">4. ⚡ Flow State vs Hyperfocus</h3>
      <p>
        Flow is a state of full concentration where the brain suppresses the Default Mode Network (mind-wandering system).
      </p>
      <p>
        It leads to maximum efficiency in learning and performance.
      </p>
      <p>
        Unlike ADHD hyperfocus, flow is intentional and structured, achieved through balance of challenge and skill.
      </p>

      <h3 className="text-xl font-semibold">5. 📊 Academic Impact (2026 data)</h3>
      <p>• 20–30% time lost due to switching</p>
      <p>• Strong decrease in retention with distracted study</p>
      <p>• Higher stress and fatigue levels</p>
      <p>• Focused study correlates with higher GPA outcomes</p>

      <h3 className="text-xl font-semibold">💡 Final Insight</h3>
      <p>
        Learning is not about time spent — it is about uninterrupted cognitive processing, memory encoding, and retrieval strength.
      </p>

    </CardContent>
  </Card>
</div>
            )}

      {/* FOCUS */}
      {page === "focus" && (
<div className="px-8 py-16 max-w-5xl mx-auto space-y-10">
  <div className="grid md:grid-cols-3 gap-4">
    <img src="https://images.unsplash.com/photo-1515879218367-8466d910aaa4" className="rounded-xl shadow" />
    <img src="https://images.unsplash.com/photo-1484417894907-623942c8ee29" className="rounded-xl shadow" />
    <img src="https://images.unsplash.com/photo-1511707171634-5f897ff02aa9" className="rounded-xl shadow" />
  </div>

  <Card>
    <CardContent className="p-6 space-y-5">

      <h2 className="text-3xl font-bold">⚡ Focus = system design, not willpower</h2>

      <p>
        Neuroscience shows focus is a limited resource. If you waste it resisting distractions, you have less left for learning.
      </p>

      <h3 className="text-xl font-semibold">1. 📵 The "Other Room" Phone Rule</h3>
      <p>
        Even a turned-off phone reduces cognitive capacity.
      </p>
      <p>
        Your brain uses energy resisting the urge to check it — draining focus.
      </p>
      <p>
        ✔ Solution: Put your phone in another room or out of sight completely.
      </p>

      <h3 className="text-xl font-semibold">2. ⏱ Flowtime Technique</h3>
      <p>
        Fixed timers can interrupt deep focus states.
      </p>
      <p>
        Flowtime uses natural focus cycles — work until energy drops, then rest.
      </p>
      <p>
        This supports deeper concentration and better retention.
      </p>

      <h3 className="text-xl font-semibold">3. 🎯 Micro-Goals</h3>
      <p>
        Vague goals reduce action. The brain needs clear starting points.
      </p>
      <p>
        Replace “study biology” with “answer 5 questions” or “summarize 1 page.”
      </p>
      <p>
        Each completed micro-task triggers dopamine, reinforcing motivation.
      </p>

      <h3 className="text-xl font-semibold">4. 🧠 Environmental Priming</h3>
      <p>
        Your brain associates environments with behavior patterns.
      </p>
      <p>
        A dedicated clean desk becomes a “focus trigger.”
      </p>
      <p>
        Clutter creates competing visual inputs that reduce attention.
      </p>

      <h3 className="text-xl font-semibold">5. 🔁 Switching Cost Problem</h3>
      <p>
        Every context switch can take up to ~20 minutes to fully recover focus.
      </p>
      <p>
        Batching shallow tasks reduces repeated cognitive resets.
      </p>
      <p>
        Close unrelated tabs to reduce background mental load.
      </p>

      <h3 className="text-xl font-semibold">6. 🔋 Biological Foundations</h3>
      <p>
        Focus depends on sleep, hydration, and stable energy levels.
      </p>
      <p>
        Even mild dehydration reduces cognitive performance significantly.
      </p>
      <p>
        Use breaks and proper nutrition to maintain attention stability.
      </p>

      <h3 className="text-xl font-semibold">🚀 Final Rule</h3>
      <p>
        Don’t rely on discipline alone. Engineer your environment so focus becomes automatic.
      </p>

    </CardContent>
  </Card>
</div>
      )}

      {/* PLANNER */}
      {page === "planner" && (
        <div className="px-8 py-16 max-w-5xl mx-auto grid md:grid-cols-2 gap-6">
          <Card>
            <CardContent className="p-6 space-y-4">
              <h2 className="text-2xl font-bold">Planner</h2>

              <Input
                type="date"
                value={selectedDate}
                onChange={(e) => setSelectedDate(e.target.value)}
              />

              <div className="flex gap-2">
                <Input
                  placeholder="Add task"
                  value={taskInput}
                  onChange={(e) => setTaskInput(e.target.value)}
                />
                <Button onClick={addTask}>Add</Button>
              </div>

              <ul className="space-y-2">
                {tasks.map((t, i) => (
                  <li
                    key={i}
                    className="flex justify-between bg-gray-50 p-2 rounded"
                  >
                    <label className="flex gap-2 items-center">
                      <input
                        type="checkbox"
                        checked={t.done}
                        onChange={() => toggleTask(i)}
                      />
                      <span className={t.done ? "line-through" : ""}>
                        {t.text}
                      </span>
                    </label>
                    <button onClick={() => deleteTask(i)}>✕</button>
                  </li>
                ))}
              </ul>
            </CardContent>
          </Card>

          <Card className="text-center">
            <CardContent className="p-6 space-y-4">
              <h2 className="text-2xl font-bold">Focus Timer</h2>
              <div className="text-5xl font-semibold">
                {formatTime(time)}
              </div>
              <Button onClick={() => setRunning(!running)}>
                {running ? "Pause" : "Start"}
              </Button>
            </CardContent>
          </Card>
        </div>
      )}
    </div>
  );
}
